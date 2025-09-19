# 🏨 Hotel Management System (Java)

This project is a **console-based Hotel Management System** implemented in Java.
It allows booking rooms, ordering food, checking availability, generating bills, and handling checkouts with data persistence using file serialization.

---

## 🚀 Features

* **Room Types**

  * Luxury Double Room (AC, Free Breakfast, ₹4000/day)
  * Deluxe Double Room (Non-AC, Free Breakfast, ₹3000/day)
  * Luxury Single Room (AC, Free Breakfast, ₹2200/day)
  * Deluxe Single Room (Non-AC, Free Breakfast, ₹1200/day)

* **Customer Management**

  * Book single or double rooms
  * Store customer details (Name, Contact, Gender)
  * Support for two customers in a double room

* **Food Ordering System**

  * Menu:

    1. Sandwich - ₹50
    2. Pasta - ₹60
    3. Noodles - ₹70
    4. Coke - ₹30
       
  * Multiple food orders can be placed per room

* **Billing & Checkout**

  * Generates a detailed bill (Room + Food charges)
  * Deallocation of room after checkout

* **Data Persistence**

  * Uses `ObjectOutputStream` & `ObjectInputStream` to save and load booking data (`backup` file).

---

## 📂 Project Structure

```
.
├── Main.java          # Main class to run the program
├── backup             # Auto-generated file to store hotel data
└── README.md          # Project documentation
```

---

## ⚙️ How to Run

1. **Clone or Download** the repository.
2. Open the project in any Java IDE (Eclipse/IntelliJ/NetBeans) or use terminal.
3. Compile the program:

   ```sh
   javac Main.java
   ```
4. Run the program:

   ```sh
   java Main
   ```
5. Follow the console menu to interact with the system.

---

## 📋 Menu Options

When you run the program, you will see:

```
Enter your choice :
1. Display room details
2. Display room availability
3. Book
4. Order food
5. Checkout
6. Exit
```

---

## 💾 Data Persistence

* All customer and booking data is stored in a `backup` file automatically when the program exits.
* When restarted, it loads data from `backup` so no bookings are lost.

---

## 🛠️ Technologies Used

* **Java SE (Core Java)**
* **File I/O (Serialization)**
* **OOP Principles (Inheritance, Polymorphism, Encapsulation)**
* **Multithreading (for file saving)**

---

## 📌 Future Improvements

* Add **GUI (JavaFX/Swing)** for better usability.
* Implement **database support** (MySQL/PostgreSQL) instead of file serialization.
* Add **payment gateway integration**.
* Generate **PDF bills** for customers.

---

## 👨‍💻 Author

Developed by **Souvik Biswas** ✨

