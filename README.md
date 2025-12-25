# 🎮 Ultimate Hangman (Raylib)

A modern Hangman game built using **C++ and raylib**, featuring multiple difficulty levels, hints, an on-screen keyboard, and smooth graphical visuals.

---

## 📌 Features

* 🎯 **3 Difficulty Levels**: Easy, Medium, Hard
* 💡 **Hints for every word**
* ⌨️ **Virtual on-screen keyboard** (mouse + keyboard support)
* ❤️ **Limited lives with hangman graphics**
* 🎨 **Gradient background and polished UI**
* 🏆 **Career-style progression** through levels

---

## 🛠️ Technologies Used

* **C++**
* **raylib graphics library**

---

## ▶️ How to Run

1. Make sure **raylib** is installed on your system
2. Compile the project:

   ```bash
   g++ main.cpp -o hangman -lraylib -std=c++17
   ```
3. Run the game:

   ```bash
   ./hangman
   ```

*(Compilation command may vary depending on your OS)*

---

## 🎮 How to Play

* Press **ENTER** to start the game
* Guess letters using:

  * Physical keyboard **OR**
  * On-screen keyboard with mouse
* Each wrong guess costs a life
* Use hints to help you guess
* Complete all levels to become the **Champion** 🏆

---

## 📂 Project Structure (Logical Modules)

* **Game Setup & Data** – constants, colors, structs, levels
* **Initialization Logic** – level start, keyboard setup
* **Graphics Module** – background, hangman drawing
* **Main Loop** – input handling, game states, rendering

---

## 👥 Team Contribution

This project is designed so different modules can be explained and maintained independently, making it ideal for academic and team-based learning.

---

## 📜 License

This project is for **educational purposes**.


