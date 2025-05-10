# 🎨 Unlimited Colours — Background Color Changer

This is a simple and interactive web project that dynamically changes the background color of the webpage every second when the **Start** button is clicked, and stops the color changes when the **Stop** button is clicked.

## 🧠 Features

- **Random Hex Color Generation**: A JavaScript function generates a new random hexadecimal color every second.
- **Start/Stop Buttons**: Users can start and stop the background color change at will.
- **Clean UI**: Styled using responsive CSS with hover effects and button transitions.

---

## 📁 Project Structure

### 1. `index.html`
- Contains the main layout with a heading and two buttons (`Start` and `Stop`).
- Links the external CSS files and includes the JavaScript script.
- Minimal inline styling to set initial background and text color.

### 2. `style.css`
- Provides styling for the entire layout:
  - Flexbox-based centering.
  - Custom fonts, button styles, and responsive typography.
  - Hover and active effects on buttons for better UX.
  - Media queries for responsiveness on smaller devices.

### 3. `script.js`
- Defines the logic for random color generation using a custom `randomColor()` function.
- Handles background color change with `setInterval()` and `clearInterval()` functions.
- Ensures that color change doesn’t stack or run multiple intervals simultaneously.
- Listens for click events on the `Start` and `Stop` buttons.

---

## 🛠️ Technologies Used

- **HTML5**  
- **CSS3**  
- **JavaScript (ES6)**  

---

## 🚀 How to Run

1. Clone or download this repository.
2. Open `index.html` in any modern browser.
3. Click **Start** to begin the background color transitions.
4. Click **Stop** to freeze the current color.

---
