# Signature_canva_project
# ✍️ Signature Canvas Web App 🎨

Welcome to the **Signature Canvas Web App** – a fun and interactive tool where users can draw, customize, save, and retrieve their digital signatures or doodles using an HTML5 canvas! 🖌️✨

---

## 🚀 Features

- 🎨 **Text Color Picker** – Choose any color to draw
- 🖼️ **Canvas Background Changer** – Select your favorite background
- 🔠 **Font Size Selector** – Change the brush width dynamically
- 🔄 **Clear Button** – Instantly clear the canvas
- 💾 **Save & Download** – Save your drawing and download it as an image
- ♻️ **Retrieve** – Load previously saved drawings from local storage

---

## 📁 File Structure

│
├── index.html # Main HTML file
├── style.css # CSS styles for layout and design
├── script.js # JavaScript for canvas and button functionalities
├── signature.png # Favicon image
└── README.md # This documentation file


---

## 🔧 Technologies Used

- ✅ HTML5
- 🎨 CSS3 + Bootstrap 4
- ⚙️ JavaScript (Vanilla JS)
- 🧠 Local Storage API



## 🧪 How to Run Locally

1. Clone the repository or download the ZIP 📥
2. Place all files in one folder:
   - `index.html`
   - `style.css`
   - `script.js`
   - `signature.png` (for favicon)
3. Open `index.html` in any modern browser 🌐
4. Start drawing your signature! 🖋️

---

## 🧠 How It Works

- The **canvas** listens for mouse events (`mousedown`, `mousemove`, `mouseup`) to draw lines.
- You can dynamically change:
  - Stroke color
  - Line width (Font size)
  - Background color
- Save your creation as an image 🖼️ using `canvas.toDataURL()` and trigger download.
- It also stores the signature in **localStorage** and can retrieve it later.

---

🛠️ Future Improvements
✏️ Add handwriting smoothing

📱 Make it mobile-friendly with touch support

☁️ Save to cloud or user profile

🙌 Author
Made with ❤️ by Yadnyesh Chaudhari
