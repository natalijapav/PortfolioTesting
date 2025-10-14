# 🟢 POST Request Test

In this test, I verify whether the API correctly creates a new resource when a POST request is sent.

---

## 🔹 Endpoint
{{base_url}}/user

---

## 🔹 Test Description
This test checks if the server accepts valid data and returns the expected response with a `201 Created` status code.  
I also verify that all submitted parameters are correctly saved and returned in the response body.

---

## 🔹 Request Body (example)
```json

{
  "id": 852,
  "username": "Patrik",
  "firstName": "Patrik",
  "lastName": "Star",
  "email": "patrik@star.com",
  "password": "ps2025",
  "phone": "123456789",
  "userStatus": 0
}

