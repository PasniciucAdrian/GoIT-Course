# Exercise11 – Trello API Test Automation with Postman

This folder contains the full solution for Homework 11 of the GoIT Manual QA course. The task involved testing the Trello API by simulating the lifecycle of a card using Postman, and verifying each step through automated tests.

---

## 🎯 Objectives

- Create and manage a Trello board, list, and card via API requests
- Use Postman to send requests with appropriate HTTP methods
- Write and validate tests using the “Tests” tab in Postman
- Document actions with screenshots and visual confirmations

---

## 🔁 Steps Completed

1. **Manually created a Trello board**
   - Shown in Trello UI with no initial lists

2. **GET request to retrieve all boards**
   - Verified response includes the manually created board
   - Board ID extracted for future use

3. **POST request to create a new list on the board**
   - Status 200 validated through Postman test
   - List ID saved

4. **GET request to retrieve list details**
   - Test confirms that list name matches the expected value

5. **POST request to create a card in the new list**
   - Response status is 200 (validated)
   - Card name: “Am creat un card in lista”

6. **GET request to retrieve card info**
   - Tests check if card name is correctly returned

7. **PUT request to update card name**
   - New name: “NumeNouPentruCard”
   - Status 200 confirmed
   - Visual confirmation in Trello board

8. **GET request to verify updated name**
   - Two assertions:
     - Name matches string directly
     - Name matches environment variable

9. **DELETE request to remove card**
   - Status 200 validated
   - Card visually removed from Trello

---

## 🛠️ HTTP Methods Used

| Action              | Method  | Endpoint Example                                 |
|---------------------|---------|--------------------------------------------------|
| Retrieve boards     | GET     | `/members/me/boards`                            |
| Create list         | POST    | `/1/lists`                                      |
| Retrieve list info  | GET     | `/1/lists/{id}`                                 |
| Create card         | POST    | `/1/cards`                                      |
| Retrieve card info  | GET     | `/1/cards/{id}`                                 |
| Update card         | PUT     | `/1/cards/{id}?name=newName`                   |
| Delete card         | DELETE  | `/1/cards/{id}`                                 |

---

## ✅ Results

- All API calls responded with status **200 OK**
- All test scripts in Postman **passed successfully**
- Actions were visually confirmed in the Trello web interface
- Screenshots were taken and explained in the attached PDF

---

## 📂 Files

- `Requirements Homework 11.pdf` – assignment instructions
- `Printscreen explanations.pdf` – screenshots and description of each step and result

