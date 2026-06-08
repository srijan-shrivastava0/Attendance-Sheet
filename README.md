# 📋 Attendance Sheet

A responsive, modern web application designed to simplify student attendance tracking for educators. Built with vanilla HTML, CSS, and JavaScript, it integrates seamlessly with Google Sheets for real-time data management.

---


---

## ✨ Features

- **One-Click Attendance** — Direct link to a Google Sheets attendance tracker for fast, paperless record-keeping
- **Student Roster Carousel** — Interactive Swiper.js slider to browse registered students
- **Dark / Light Mode** — User-selectable theme with persistent preference via `localStorage`
- **Scroll Animations** — Smooth entrance animations powered by ScrollReveal.js
- **Responsive Design** — Fully mobile-friendly layout with a collapsible navigation menu
- **Active Navigation Highlighting** — Navigation links update automatically based on scroll position
- **Scroll-to-Top Button** — Appears after scrolling 200px for quick page navigation

---

## 🛠️ Built With

| Technology | Purpose |
|---|---|
| HTML5 | Page structure & semantic markup |
| CSS3 | Styling, theming, and responsive layout |
| JavaScript (ES6+) | Interactivity and DOM manipulation |
| [Swiper.js](https://swiperjs.com/) `v6.6.2` | Touch-enabled student card carousel |
| [ScrollReveal.js](https://scrollrevealjs.org/) | Scroll-triggered entrance animations |
| [Remix Icons](https://remixicon.com/) | Icon library |
| Google Sheets | Backend attendance data storage |

---

## 📁 Project Structure

```
Attendance-Sheet/
└── Attendance Sheet/
    ├── index.html          # Main entry point
    └── assets/
        ├── css/
        │   ├── styles.css              # Custom styles
        │   └── swiper-bundle.min.css   # Swiper CSS
        ├── js/
        │   ├── main.js                 # Core application logic
        │   ├── swiper-bundle.min.js    # Swiper library
        │   └── scrollreveal.min.js     # ScrollReveal library
        ├── img/                        # Images and favicon
        └── scc/                        # Additional assets
```

---

## 🚀 Getting Started

### Prerequisites

No build tools or dependencies required. Just a modern web browser.

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/srijan-shrivastava0/Attendance-Sheet.git
   ```

2. **Navigate to the project folder**
   ```bash
   cd "Attendance-Sheet/Attendance Sheet"
   ```

3. **Open in your browser**
   ```bash
   # Simply open index.html in any browser, or use a live server:
   npx live-server
   ```

### Connect Your Google Sheet

1. Open your Google Sheet for attendance tracking.
2. Click **Share** → set access to *Anyone with the link*.
3. Copy the sheet URL and replace the existing Google Sheets links in `index.html`:
   ```html
   <a href="YOUR_GOOGLE_SHEET_URL" class="button">Take Attendance</a>
   ```

---

## 📖 Usage

| Section | Description |
|---|---|
| **Home** | Landing page with a direct "Take Attendance" button |
| **Attendance Taken** | Overview of the attendance process and Google Sheets integration |
| **List of Students** | Swipeable carousel of registered student cards |
| **More** | Additional resources and Google Sheets links |

---

## 🎨 Theming

The app supports **Dark Mode** and **Light Mode**. The user's preference is automatically saved in `localStorage` and restored on the next visit.

Toggle the moon/sun icon in the navigation bar to switch themes.

---

## 📊 Stats Highlighted

- **1,000+** Students Registered
- **650+** Teachers Registered

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/your-feature-name`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/your-feature-name`
5. Open a Pull Request

---

## 📄 License

This project is open source and available under the Creative Commons Legal Code

CC0 1.0 Universal

---

## 👤 Author

**Srijan Shrivastava**

- GitHub: [@srijan-shrivastava0](https://github.com/srijan-shrivastava0)

---

> Made with ❤️ to make attendance simple for educators everywhere.
