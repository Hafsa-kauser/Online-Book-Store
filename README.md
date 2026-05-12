
# Online Bookstore 

## Objective
The Online Bookstore is a simple full-stack web application where users can browse books, view details, manage a shopping cart, and complete checkout. The project demonstrates a basic e-commerce workflow using Java and Spring MVC.

---

## Features

### Homepage
- Displays a list of available books
- Each book includes:
  - Title
  - Author
  - Price
- Search bar to find books by name


---

### Cart Page
- Displays all selected books
- Shows total price
- Option to remove items from the cart

---

### Checkout Page
- Simple checkout process
- Displays an order confirmation message after successful checkout

---

## Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Java
- Spring MVC (Spring Web)

### Database (Optional)
- JDBC
- MySQL or any relational database

---

## REST API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/books` | Fetch all books |
| GET | `/books/{id}` | Fetch book details |
| POST | `/cart` | Add book to cart |
| GET | `/cart` | Get cart items |
| DELETE | `/cart/{id}` | Remove item from cart |
| POST | `/checkout` | Place order |

---

## Project Structure

```

OnlineBookstore/
│
├── src/
│   ├── controller/
│   ├── service/
│   ├── dao/
│   ├── model/
│
├── WebContent/
│   ├── jsp/
│   ├── css/
│   ├── js/
│
├── WEB-INF/
│   ├── web.xml
│
├── pom.xml

```

---

## Learning Outcomes
- Frontend development using HTML, CSS, JavaScript
- Backend development using Spring MVC and Java
- Understanding REST API design and implementation
- Database integration using JDBC (optional)
- Handling cart and checkout workflows

