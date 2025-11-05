# 🟢 PUT Request Test  

In this test, I verify whether the API correctly updates a status from available to sold for an existing pet when a **PUT** request is sent.  

---

## 🔹 Endpoint  
`{{base_url}}/pet/11111`  

---

## 🔹 Test Description  
The purpose of this test is to confirm that the server:  
- Accepts valid update data for an existing user  
- Returns a **200 OK** status code  
- Reflects all modified fields correctly in the response body  
- Keeps unchanged fields intact  

---

## 🔹 Preconditions  
- The user already exists in the system (created previously via **POST**).  
- Correct username is provided in the URL.  

---

## 🔹 Request Example  
**Method:** PUT  

**Body (raw JSON):**  
```json
{
  "id": 11111,
  "category": {
    "id": 0,
    "name": "Duggeeeee"
  },
  "name": "Duggee",
  "photoUrls": [
    "string"
  ],
  "tags": [
    {
      "id": 0,
      "name": "Dagi"
    }
  ],
  "status": "sold"
}

```
---

### 📝 Note / Observation

After sending `PUT /pet` with `"status": "sold"`, the subsequent `GET /pet/{petId}` request still returns `"status": "available"`.

**Expected behavior:**  
The API should update the pet’s status to `"sold"` and reflect the change when retrieving the pet by ID.

**Actual behavior:**  
The API accepts the update request (returns 200 OK), but the status remains `"available"` when verified via `GET /pet/{petId}`.  
This indicates that the update operation does not persist the new status value.

➡️ **This would be reported as a bug in a real production environment**, since the response suggests a successful update, but the system state remains unchanged.

---

### 🐞 Bug Report

**Bug ID:** PetStoreApi 1
**Module:** Pet  
**Title:** PUT `/pet` does not update pet status in the system  
**Severity:** Medium  
**Priority:** High  

**Precondition:**  
Pet with ID `11111` exists and has status `"available"`.

**Steps to Reproduce:**
1. Send `PUT /pet` with the following body:
   ```json
   {
     "id": 11111,
     "category": {
       "id": 0,
       "name": "Duggeeeee"
     },
     "name": "Duggee",
     "photoUrls": ["string"],
     "tags": [
       {
         "id": 0,
         "name": "Dagi"
       }
     ],
     "status": "sold"
   }

   ```
   ---

2. Verify response → API returns **200 OK**.
3. Send `GET /pet/11111` to check the updated status.

**Expected Result:**  
The `"status"` field in the response should display `"sold"`.

**Actual Result:**  
The `"status"` field remains `"available"` despite the successful update response.

---


