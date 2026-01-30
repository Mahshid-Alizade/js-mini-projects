# ⏱️ Countdown Timer App

A simple and interactive Countdown Timer built using HTML, CSS, and JavaScript.  
The app focuses on clean UI design and core JavaScript timing functions such as setInterval() and clearInterval() to handle user interactions and countdown logic.

---

## 🚀 Features

- User-friendly interface
- Dynamic countdown functionality
- Visual feedback at each stage
- Audio notification when the timer ends

---

## 🛠️ Technologies Used

- HTML – Structure of the application  
- CSS – Styling and layout of the UI  
- JavaScript – Timer logic and interactions  
  - setInterval()
  - clearInterval()

---

## 📋 How the App Works (Step-by-Step)

### 1️⃣ Welcome Screen
When the app loads, a welcome message is displayed to guide the user.

![Welcome Screen](images/step1-welcome.png)

---

### 2️⃣ Time Input
The user enters the desired countdown time and presses Enter to start the timer.

![Time Input](images/step2-input.png)

---

### 3️⃣ Countdown in Progress
The timer starts counting down in real time using setInterval().

![Countdown Running](images/step3-countdown.png)

---

### 4️⃣ Time Over Alert
Once the countdown reaches zero:
- A “Time Over” message is displayed
- A bell sound is played
- The interval is stopped using clearInterval()

![Time Over Screen](images/step4-finish.png)

---

## 📸 Demo

Below is an example screenshot of the application:

![Timer App Demo](images/demo.png)

---

## 📌 Notes

- Images should be placed inside an images/ folder.
- Audio is triggered automatically when the timer finishes.
- The project is ideal for practicing JavaScript timing functions and DOM manipulation.

---

## ✨ Future Improvements (Optional)

- Pause / Resume functionality
- Multiple timers
- Mobile responsiveness
- Custom alarm sounds
