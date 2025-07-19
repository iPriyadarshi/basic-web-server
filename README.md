# 🌐 Basic Web Server using Node.js and Express

A simple web server built with **Node.js**, **Express.js**, and **EJS** templating engine. This project demonstrates how to set up routes, render dynamic views, and serve static files using Express.

---

## 📁 Project Structure

```
basic-web-server/
├── public/                # Static assets (CSS)
│   └── style.css
├── views/                 # EJS templates
│   ├── index.ejs
│   ├── about.ejs
│   ├── contact.ejs
│   └── 404.ejs            # Custom 404 page
├── app.js                 # Main Express server file
├── package.json           # Project metadata & dependencies
├── .gitignore             # Git ignore rules
├── LICENSE                # MIT License
└── README.md              # Project documentation
```

---

## 🚀 Getting Started

### ✅ Prerequisites

* [Node.js](https://nodejs.org/)
* [npm](https://www.npmjs.com/)
* [Git](https://git-scm.com/)

---

## ⚙️ Installation

1. Clone the repo:

```bash
git clone https://github.com/iPriyadarshi/basic-web-server.git
cd basic-web-server
```

2. Install dependencies:

```bash
npm install
```

---

## ▶️ Running the Server

```bash
# Start the server
npm start

# OR use nodemon for auto-reload (after installing it)
npm run dev
```

Then open your browser and go to:
🌍 [http://localhost:3000](http://localhost:3000)

---

## 🔨 Features

* 🨭 Route handling for `/`, `/about`, and `/contact`
* 📄 Dynamic HTML rendering using **EJS**
* 🎨 Static file serving (CSS via `/public`)
* ⚠️ Custom 404 error page for unmatched routes

---

## 💡 Learnings

This project helps you understand:

* Express app structure
* EJS template rendering
* Static file serving with `express.static`
* Basic project organization
* Custom error handling (404)
* Setting up a local development server

---

## 📜 Scripts

```json
"scripts": {
  "start": "node app.js",
  "dev": "nodemon app.js"
}
```

> Use `npm run dev` for hot reloading (requires `nodemon`)

---

## 📄 License

Licensed under the [MIT License](LICENSE).

---
