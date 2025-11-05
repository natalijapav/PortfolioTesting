# 🧪 Swagger Petstore API Testing with Postman

This project showcases my **API testing practice** using the [Swagger Petstore](https://petstore.swagger.io) demo API.  
The goal was to practice designing, executing, and validating **API requests and responses** in **Postman**, through realistic QA workflows and mini end-to-end scenarios.

---

## 🔗 API Under Test

- **Base URL:** `https://petstore.swagger.io/v2`
- Official Swagger UI: (Swagger Petstore v2)

I organized the project into two main folders — each representing a functional area of the API I tested.

- **Pet** – managing pets in the store
- **User** – managing users, login/logout, etc.

---

## 🧰 Tools & Stack

- **Postman** – for sending requests and writing test scripts
- **JavaScript (Postman tests)** – assertions and variable handling
- **GitHub** – to store collection, environment and documentation

---

---

### 🐞 Bug Summary Table

| **Bug ID** | **Module** | **Endpoint** | **Description** | **Severity** | **Status** | **Reproducibility** |
|-------------|-------------|--------------|------------------|---------------|-------------|----------------------|
| **PetStoreApi 1** | Pet | `PUT /pet` | Pet status not updated after sending `"status": "sold"` – GET still returns `"available"`. 


---

📋 **Notes:**
- Bugs were observed on the public Swagger Petstore demo API (`https://petstore.swagger.io/v2`).
- These findings are kept as **QA practice examples**, not production defects.
- Each issue was verified through Postman requests and validated with `GET` follow-up checks.

---

