# Quiz App 🧠

An interactive quiz application built with Node.js, Express, and EJS. Users can sign up, log in, and take quizzes. Their progress is saved, and scores are displayed on a leaderboard.

---

## 🚀 Features

- 🔐 User Authentication (Sign Up / Login)
- 🔑 Passwords securely hashed using bcrypt
- 🧾 Dynamic Quiz Questions from JSON
- 📊 Leaderboard to track high scores
- 🖼️ Clean UI with EJS templating
- 🧩 Modular code structure with routes, controllers, and middleware
- 🌓Dark/Light Mode

### 🧠 Gameplay Enhancements

- ⏱️ Countdown Timer per Question
- ✅ Answer validation with visual feedback
  (Correct = green | Incorrect = red )
- 🎉 Confetti animation when user answers correctly 
  (Uses Canvas Confetti with custom color palette)
- 🌈 Glowing animation effect on correct answers
- 🔁 Auto-next after answer selection
- 📥 Ability to select number of quiz questions before starting


---

## 📂 Project Structure
```plaintext
bin/        # Executable scripts
routes/     # Express route definitions
controllers/ # Logic handling route requests
middleware/ # Express middleware functions
data/       # JSON data files
views/      # EJS template files
public/     # Static files (CSS, JS, images)
```

---

## 🛠️ Installation & Running the App

**Clone the repository**
   ```bash
   git clone https://github.com/i-nafis/CSCI355-Project-2
```
**Install dependencies**  
   ```bash
   npm install
```
**Run the application**
```bash
  node bin/www
```
**Open in browser**
```bash
http://localhost:3000
```
## 👥 Team Members

- Castillo, Abraham  
- Islam, Nafisul  
- Rahi, Mst  
- Wong, Jessica  

---

## 🌐 Deployment

🔗 **Live App**: [https://quiz.afk.ac](https://quiz.afk.ac)

---


## 📝 License

This project is for academic purposes only. All rights reserved by the team.

---

## 💡 Future Improvements

- Add admin dashboard to manage questions  
- Quiz history  
- Add categories and difficulty levels for quizzes  
- Connect to a real database (MongoDB)
