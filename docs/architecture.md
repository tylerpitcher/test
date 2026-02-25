# Architecture

Test API follows a standard layered architecture pattern.

---

## 🏛 Layers

### 1️⃣ Controller Layer

- Handles HTTP requests
- Performs request validation
- Maps endpoints to service calls

### 2️⃣ Service Layer

- Contains business logic
- Coordinates repository operations
- Handles domain rules

### 3️⃣ Repository Layer

- Interfaces with database
- Uses Spring Data JPA

---

## 🔄 Request Flow
