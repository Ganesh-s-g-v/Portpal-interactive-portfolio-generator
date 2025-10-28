# 🎨 Portpal - An Interactive Portfolio Generator

An elegant and fully responsive **React.js-based portfolio generator** that enables users to instantly create, preview, and share professional portfolio websites. With an intuitive interface and smooth performance, it allows users to input their details, view real-time updates, and generate a personalized shareable portfolio link — all in one place.

---

## 🚀 Features

* **Real-time Portfolio Editing** – Instantly view changes as you edit personal details like name, about section, projects, and contact info.
* **Auto-generated Shareable Link** – Generate a unique URL to share your portfolio with anyone in one click.
* **Responsive Design** – Optimized for all screen sizes (desktop, tablet, and mobile).
* **Lightweight Deployment** – Simple build and deployment process using Netlify or Vercel.
* **Clean UI/UX** – Minimalistic layout emphasizing professionalism and readability.
* **Client-Side Routing & State Management** – Smooth transitions and consistent user experience using React state.

---

## 🧩 Tech Stack

| Category            | Technologies                            |
| ------------------- | --------------------------------------- |
| **Frontend**        | React.js, HTML5, CSS3, JavaScript (ES6) |
| **Styling**         | Tailwind CSS                            |
| **Build Tool**      | Vite                                    |
| **Deployment**      | Netlify                                 |
| **Version Control** | Git & GitHub                            |

---

## 📂 Folder Structure

```
portfolio-generator/
│
├── public/               # Static files
├── src/                  # Core source code
│   ├── components/       # Reusable UI components
│   ├── assets/           # Images, icons, etc.
│   ├── App.jsx           # Main app file
│   └── main.jsx          # React DOM render entry
│
├── dist/                 # Production build files
├── package.json          # Project metadata and dependencies
├── tailwind.config.js    # Tailwind configuration
├── postcss.config.js     # PostCSS configuration
└── README.md             # Documentation (this file)
```

---

## ⚙️ Installation and Setup

Follow these steps to set up the project locally:

1. **Clone the repository**

   ```bash
   git clone https://github.com/Ganesh-s-g-v/interactive-portfolio-generator.git
   cd interactive-portfolio-generator
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the development server**

   ```bash
   npm run dev
   ```

4. **Build for production**

   ```bash
   npm run build
   ```

5. **Preview the production build**

   ```bash
   npm run preview
   ```

---

## 🌐 Deployment (Netlify)

1. Log in to [Netlify](https://www.netlify.com/).
2. Click **“Add New Site” → “Import an existing project.”**
3. Connect your **GitHub repository**.
4. In build settings, set:

   * **Build Command:** `npm run build`
   * **Publish Directory:** `dist`
5. Click **Deploy Site** — Netlify will handle the rest!

---

## 📸 Demo Preview

Example:

> 🔗 **Live Demo:** [https://portpal.netlify.app/](https://portpal.netlify.app/)


---

## 🧠 How It Works

1. Users fill out their personal and professional details.
2. The app dynamically updates the portfolio preview in real time.
3. When the “Share” button is clicked, a unique portfolio link is generated.
4. Visitors who open this link see a **clean, view-only version** of the portfolio — without the edit or share options.

---

## 💡 Future Enhancements

* Custom domain linking
* Dark/light theme support
* Portfolio PDF export
* Integrated analytics dashboard
* Template selection for portfolio styles

---

## 🧑‍💻 Author

**Ganesh Vardhan**
Frontend Developer & Tech Enthusiast
🔗 [GitHub](https://github.com/Ganesh-s-g-v)

---

