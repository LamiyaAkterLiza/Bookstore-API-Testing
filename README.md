# 📘 Bookstore API Testing Documentation

-->This repository contains API test cases for evaluating the Bookstore REST API provided at [Website](https://bookstore.demoqa.com). 

-->All test cases are written and executed using Postman, focusing on user creation, book listing, token generation, authentication, and book assignment.

---

## ✅ Test Cases & Descriptions

📚 Test Book Listing 
- **Method**: `GET`
- **Objective**: Fetch all available books from the store.

✅ Create a New User
- **Method**: `POST`
- **Objective**: Create a new user account using a username and password.

✅ Assign Books to User
- **Method**: `POST`
- **Objective**: Assign two books to a registered user using their userId and book isbn.
- **Security**: Requires Basic Authentication.

✅ Generate Token
- **Method**: `POST`
- **Objective**: Generate an authentication token using username and password.

✅ Verify Login Authorization
- **Method**: `POST`
- **Objective**: Verify if the provided user credentials are valid.

## 🚀 How to Run Tests  
1. Open **Bookstore_Site** [Website](https://bookstore.demoqa.com)
2. Use **Postman** to open json file for focusing on user creation, book listing, token generation, authentication, and book assignment.
3. Use **Newman** for automation test report.  





