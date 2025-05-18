
# 📚 Online Library

An interactive web application for managing books in a simple digital library. Users can input their name, the book's title, select the genre, and have it stored in the browser using **Local Storage**. All entries are displayed in a dynamic table with the issue date and genre.

---

## 🌐 Demo

🔗 [Live Demo](#)  
> Replace the `#` with the actual link if deployed on Netlify, GitHub Pages, Vercel, etc.

---

## ✨ Features

- ✅ Add book entries with reader name and genre.
- 🕒 Auto-generate and save the date of issue.
- 📁 Save and persist data using **Local Storage**.
- 📃 Display all book entries in a clean table format.
- 🧹 Data stays saved even after refreshing the page.
- 🎨 Built with **Bootstrap 5** for responsive UI.
- 🔎 Navbar with integrated search input (UI only).

---

## 🛠️ Tech Stack

- **HTML5**
- **CSS3** (Bootstrap 5)
- **JavaScript (Vanilla JS)**
- **Local Storage API**

---

## 📸 Preview

![Online Library Screenshot](./assets/screenshot.png)
> Save the image you uploaded as `screenshot.png` inside an `assets/` folder

---

## 📁 Project Structure

```
online-library/
├── index.html         # Main HTML file
├── style.css          # (Optional) Custom styles
├── script.js          # JS logic for form & localStorage
└── assets/
    └── screenshot.png # App preview image
```

---

## 🚀 Getting Started

### 🔧 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-library.git
   ```

2. Navigate to the project directory:
   ```bash
   cd online-library
   ```

3. Run the project:
   - Open `index.html` directly in your browser.
   - Or use a live server like VS Code extension **Live Server**.

> No build steps or dependencies required — it’s fully client-side.

---

## 🧠 How It Works

- When the user submits the form, data is validated and saved in the browser's localStorage.
- A new row is added to the table dynamically.
- On every page load, saved data from localStorage is reloaded and rendered in the table.

---

## 📌 Future Enhancements

- 🗑 Add functionality to delete or edit book entries.
- 🔍 Implement actual search/filter logic in the table.
- 🧭 Sort entries by date or genre.
- 🌐 Deploy on a hosting platform with real-time database support (e.g., Firebase).

---

## 🤝 Contributing

Contributions are welcome!  
Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Mustafa Ashraf Mohamed**  
Frontend Developer | React.js & JavaScript Enthusiast  
[LinkedIn](#) • [Portfolio](#) • [Email](mailto:your-email@example.com)
