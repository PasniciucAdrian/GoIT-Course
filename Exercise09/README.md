# Exercise09 – Network Requests Analysis on makeup.ro

This folder contains the full documentation and analysis for Homework 9 of the GoIT Manual QA Course. The task involved analyzing network traffic and HTTP request methods for key actions on the website [makeup.ro](https://www.makeup.ro/), using browser developer tools.

---

## 🎯 Objective

Analyze the behavior of different user interactions on the site by observing:

- Request URLs
- HTTP methods (GET, POST, PUT, PATCH, DELETE, OPTIONS)
- Status codes
- Payload and response data

Screenshots were taken for each request and explained in dedicated PDF files.

---

## 📄 Structure


---

## 🧪 Tested Scenarios

Each scenario corresponds to a screenshot explanation PDF, including both static and dynamic interactions on the site:

### 🔹 Screenshot Explanation 1
- Opened a new browser tab
- Accessed https://makeup.ro/
- Opened developer tools to inspect requests

### 🔹 Screenshot Explanation 2
- Observed preflight OPTIONS requests (analytics)
- POST requests via XHR (JavaScript)
- GET requests for video files (206 Partial Content)
- POST ping requests with status 204 (No Content)

### 🔹 Screenshot Explanation 3
- Initial page load analysis
- Request method: GET
- Status: 200 OK
- HTML document and preview captured

### 🔹 Screenshot Explanation 4
- Product page visited (ID 553218)
- Added product to cart
- PUT request for cart update
- HTML and JSON responses reviewed

### 🔹 Screenshot Explanation 5
- Multiple products added to cart
- Performed checkout actions
- POST (submit form), PATCH (modify cart), DELETE (remove product)
- Status: 200 OK for all actions
- Server correctly handled requests

---

## 📚 Methods Summary

| Method   | Description                                      |
|----------|--------------------------------------------------|
| GET      | Retrieves data from the server                   |
| POST     | Sends data to create a new resource              |
| PUT      | Uploads and replaces resource data               |
| PATCH    | Partially updates existing data                  |
| DELETE   | Removes a resource from the server               |
| OPTIONS  | Informs which HTTP methods are supported         |

---

## ✅ Conclusion

This exercise provided hands-on experience in analyzing HTTP traffic using browser dev tools. Each action on the site (viewing, adding to cart, checking out) was traced and interpreted based on the request method and server response.

Each screenshot and explanation aligns with the requirements defined in the assignment file.


