# 📚 Book System Management

![Vue.js](https://img.shields.io/badge/Frontend-Vue.js-4FC08D?style=flat&logo=vuedotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Protocols](https://img.shields.io/badge/Protocols-SOAP%20%7C%20gRPC-blue)
![Data](https://img.shields.io/badge/Data-JSON%20Persistence-lightgrey)

**Book System** is a comprehensive full-stack web application designed to manage library resources. It demonstrates advanced backend communication by implementing both **SOAP** and **gRPC** protocols, coupled with a reactive **Vue.js** frontend.

Instead of a traditional database, this project utilizes a lightweight **JSON-based data persistence** system, making it portable and easy to deploy for demonstration purposes.

## 🚀 Features

### 👤 User Interface
* **Search & Discovery:** Users can easily search for books within the system.
* **Rating System:** Ability to rate books and leave star reviews.
* **Comments:** Users can share their thoughts on specific books.

### 🛡 Admin Panel
* **Dashboard Access:** Secure login for administrators.
* **Book Management:** Full CRUD (Create, Read, Update, Delete) capabilities.
* **Edit Metadata:** Admins can update book details, authors, and descriptions instantly.

## 🛠 Tech Stack

* **Frontend:** Vue.js (SPA Architecture)
* **Backend Runtime:** Node.js
* **Communication Protocols:**
    * **SOAP:** For structured information exchange.
    * **gRPC:** For high-performance, low-latency communication.
* **Data Storage:** JSON File System (NoSQL-like structure without external DB dependencies).

## 📸 Screenshots


|:---:|:---:|:---:|
| 
<img src="Assets/admin_panel.png" width="300"> |
<img src="Assets/admin_panel_2.png" width="300"> |
<img src="Assets/home_page.png" width="300"> |
<img src="Assets/home_page_2.png" width="300"> |
<img src="Assets/login_page.png" width="300"> |

## ⚙️ Installation & Setup

Follow these steps to get the project running on your local machine.

### 1. Clone the Repository
```bash
git clone [https://github.com/bkrgms/book-system.git](https://github.com/bkrgms/book-system.git)
cd book-system

```
2. Install Dependencies
Install the required Node.js packages for both the application and the server.
npm install

3. Run the Backend Services

Since this project uses multiple protocols, you need to start the services in separate terminal windows:
Terminal A (gRPC Service):
node grpc_client.js
Terminal B (SOAP Service):
node soap_server.js

4. Run the Frontend
In a new terminal window, start the Vue.js development server:
npm run serve
Access the application at: http://localhost:8080
