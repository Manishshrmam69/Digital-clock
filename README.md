
## 🚀 Features

- Live digital clock display (hours, minutes, seconds)
- Responsive and clean UI
- Lightweight and beginner-friendly

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)

## 🔧 How to Use

1. Clone this repository or download the ZIP.
2. Make sure all files (`index.html`, `style.css`, `index.js`) are in the same folder.
3. Open `index.html` in any modern web browser.

## 🧠 How it Works

- `index.html` creates the basic structure and layout.
- `style.css` adds styles and layout to make it visually appealing.
- `index.js` updates the time every second using `setInterval()` and JavaScript Date object.

## 📷 Preview

![Digital Clock Preview](screenshot.png) <!-- Replace with your actual screenshot path -->

## 📌 Example JavaScript Logic

```js
setInterval(() => {
  let hours = new Date().getHours();
  let minutes = new Date().getMinutes();
  let seconds = new Date().getSeconds();

  document.getElementById('hrs').innerText = hours < 10 ? '0' + hours : hours;
  document.getElementById('min').innerText = minutes < 10 ? '0' + minutes : minutes;
  document.getElementById('sec').innerText = seconds < 10 ? '0' + seconds : seconds;
}, 1000);
