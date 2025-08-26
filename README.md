# Online Quiz Application with Timer 

This project is a **web-based quiz platform** where users can take multiple-choice quizzes under a time limit.  
The system calculates and displays the user’s score at the end of the quiz.

## 📅 Project Info  
- Developed: April 2025  
- a **group project** developed for **COMP3421 Web Application Design and Development**

---

## 📂 Project Structure

```
index.php               # Main entry point of the application
quiz_list.sql           # SQL script to create and populate quiz table
src/
│── html/               # Frontend HTML templates
│── php/                # Backend PHP scripts
│── scripts/            # JavaScript (e.g., quiz logic, timer)
│── styles/             # CSS stylesheets
```

---

## ⚙️ Mechanism

- **Frontend (HTML, CSS, JavaScript):**
  - Renders quiz pages and options
  - Timer functionality using JavaScript
  - Dynamic user interaction and score display

- **Backend (PHP + MySQL):**
  - Stores quiz questions and answers
  - Processes user submissions
  - Calculates and returns quiz results

---

## 🏁 Getting Started

Follow these steps to set up and run the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/chloewongwy/quiz-app.git
   cd quiz-app
   ```

2. **Set up XAMPP**
   - Install [XAMPP](https://www.apachefriends.org/index.html).
   - Move the `src` folder into the `htdocs` directory.
   - Replace the existing `index.php` in `htdocs` with the provided `index.php`.

3. **Import the database**
   - Open **phpMyAdmin** in MySQL (http://localhost/phpmyadmin).
   - Create a database (e.g., `quiz_list`).
   - Import the `quiz_list.sql` file into the database.
   - Or run:
     ```bash
     mysql -u root -p quiz_list < "absolute_path_of_quiz_list.sql"
     ```

4. **Run the application**
   - Start Apache and MySQL from the XAMPP Control Panel.
   - Open your browser and go to:
     ```
     http://localhost/index.php
     ```

5. **Take a quiz**
   - Choose a quiz, answer within the time limit, and view your score.

---

## 📸 Visualization

Below are some screenshots of the quiz application:

- **Home Page**  
  ![Home Page]<img width="1904" height="916" alt="image" src="https://github.com/user-attachments/assets/f2c4df47-dda7-4450-afc5-20f9b5070a12" />

- **Quiz in Progress (with Timer)**  
  ![Quiz Page]<img width="1903" height="917" alt="image" src="https://github.com/user-attachments/assets/bec0bc85-8bd5-4688-8f2f-449b9960154d" />

- **Result Page**  
  ![Result Page]<img width="1905" height="915" alt="image" src="https://github.com/user-attachments/assets/a3c6f12e-dffb-4526-acd0-05e43b168a25" />

---

## 📌 Requirements

- XAMPP (Apache + MySQL + PHP)  
- Web browser with JavaScript enabled  

---
