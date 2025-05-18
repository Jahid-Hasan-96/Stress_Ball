# 🧘 Stress Ball Interactive Animation

This is a smooth, responsive web animation project that simulates a draggable stress ball with realistic spin, bounce, and squash/stretch effects. Built with HTML, CSS, JavaScript, and GSAP, this project is fun, touch-friendly, and optimized for desktop and mobile devices. You can also switch themes between a stress ball and a tennis ball!

---

## 🔥 Features

- 🎯 **Drag & Release**: Ball spins and bounces around the screen.
- 💥 **Squash & Stretch**: Realistic deformation when hitting edges.
- 🎨 **Theme Switcher**: Toggle between Stress Ball and Tennis Ball.
- 🖼️ **Responsive Design**: Works beautifully on mobile and desktop.
- 🧊 **Frosted Glass UI**: Stylish, modern look using backdrop filters.
- 🌐 **No External Image Links**: All images and favicon are loaded locally.
- 📌 **Custom Favicon**: Displays a browser tab icon.

---

## 🗂️ Project Structure

```
project-folder/
├── index.html             # Main HTML page
├── style.css              # Main stylesheet with custom properties and responsive design
├── main.js                # JavaScript logic for drag, bounce, and spin
├── favicon.ico            # Browser tab icon
└── images/
    ├── stress-ball-1.png  # Default ball
    └── tennis-ball.png    # Alternate ball for theme switcher
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Jahid-Hasan-96/Stress_Ball.git
cd Stress_Ball
```

### 2. Serve Locally (Required for Image & Favicon Support)

#### Option 1: VS Code Live Server

- Install the **Live Server** extension
- Right-click `index.html` → **Open with Live Server**

#### Option 2: Python HTTP Server

```bash
# Python 3
python -m http.server
```

Then open `http://localhost:8000` in your browser.

---

## 📱 Mobile Responsiveness

- Theme buttons stack vertically on small screens
- Ball resizes dynamically (`--ball-size`)
- Hints and headings scale for readability
- Touch interactions are optimized

No need to worry — it works great on phones!

---

## 🖼️ Screenshots

```
images/
├── screenshot-desktop.png
└── screenshot-mobile.png
```

And include them in the README:

```markdown
### Desktop View

![Desktop]((https://github.com/user-attachments/assets/d893eb50-787a-42e6-983c-e560a297468c))

### Mobile View

![Mobile](https://github.com/user-attachments/assets/5ceded37-23d5-48f0-81c4-7a7e29e19adc)
```

---

## 🛠️ Built With

- **HTML5**
- **CSS3** (custom properties, media queries, backdrop filters)
- **JavaScript (ES6)**
- **GSAP 3** with Draggable & InertiaPlugin

---

## 👤 Author

**M M Jahid Hasan**  
🔗 [GitHub Profile](https://github.com/Jahid-Hasan-96)

---

## 📄 License

This project is open-source under the MIT License.  
© 2025 M M Jahid Hasan
