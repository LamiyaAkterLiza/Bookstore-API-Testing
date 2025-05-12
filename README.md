# 📘 Bookstore API Testing Documentation

-->This repository contains API test cases for evaluating the Bookstore REST API provided at [https://bookstore.demoqa.com](https://bookstore.demoqa.com). 
-->All test cases are written and executed using Postman, focusing on user creation, book listing, token generation, authentication, and book assignment.

---

## ✅ Test Cases & Descriptions

### 📚 Test Book Listing 

- **Method**: `GET`
- **Endpoint**: `/BookStore/v1/Books`
- **Objective**: Fetch all available books from the store.
- **Expected Response**:
  - `200 OK`
  - Response JSON contains fields:
    - `isbn`, `title`, `subTitle`, `author`, `publish_date`, `pages`, `description`, `website`

### 👤 Create a New User (20 Marks)

- **Method**: `POST`
- **Endpoint**: `/Account/v1/User`
- **Request Body**:
```json
{
  "userName": "yourUsername",
  "password": "yourPassword"
}

### 👤  Assign 2 books to user with authentication




