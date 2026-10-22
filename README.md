# library-management-system
My official GitHub profile README library management system 
# 📚 Library Management System

A simple, user-friendly, and efficient **Library Management System** built to manage books, track issued books, and maintain member records easily.

---

## 🛠️ Tech Stack & Tools

* **Frontend:** HTML5, CSS3, JavaScript
* **Tools:** VS Code, Git, GitHub

---

## ✨ Key Features

* 📖 **Add & Delete Books:** Easy form to add new books or remove old ones.
* 🔍 **Search Functionality:** Search books by Title or Author.
* 🔄 **Issue & Return Books:** Track issued books easily.
* 📱 **Responsive UI:** Works smoothly on mobile and desktop.

---

## 💻 Code Snippet

```javascript
// Array to store library books
let library = [];

function addBook(id, title, author) {
    const newBook = { id: id, title: title, author: author, isIssued: false };
    library.push(newBook);
    console.log(`Book "${title}" added successfully!`);
}

addBook(101, "The Great Gatsby", "F. Scott Fitzgerald");
