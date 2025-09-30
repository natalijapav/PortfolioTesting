# PUT /pet

**Opis:**  
Ažurira informacije o ljubimcu.

**Request:**
```
PUT https://petstore.swagger.io/v2/pet
Content-Type: application/json
```
**Body:**
```json
{
  "id": 10,
  "name": "Maza",
  "status": "sold"
}
```

**Expected response:**
- Status code: `200`
- Body: JSON sa ažuriranim statusom
