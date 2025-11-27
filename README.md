# Beautiful Rose with a Message

A simple, beautiful webpage displaying a rose animation with a heartfelt message, built with **Tailwind CSS**.

![Screenshot of Beautiful Rose](docs/img/screenshot.png)

---

## **Project Structure**

```
rose-with-a-message/
├─ package.json
├─ pnpm-lock.yaml
├─ input.css          # Tailwind + custom CSS
└─ docs/
   ├─ index.html      # Main HTML
   └─ style.css       # Compiled CSS output
```

---

## **Setup & Usage**

### **1. Install dependencies**

```bash
pnpm install
```

### **2. Start Tailwind in watch mode**

```bash
pnpm run dev
```

* This will compile `input.css` to `docs/style.css` whenever you make changes.
* Keep this terminal running during development.

### **3. Open the webpage**

* Open `docs/index.html` in your browser to view the rose animation and message.

---

## **Technologies Used**

* [Tailwind CSS](https://tailwindcss.com/) – Utility-first CSS framework
* [PostCSS](https://postcss.org/) – CSS processing
* [PNPM](https://pnpm.io/) – Fast, disk space-efficient package manager

---

## **Customizations**

* **Message text** – Update the `<h1>` inside `docs/index.html`.
* **Petals & animation** – Edit `.petal` classes inside `input.css`.
* **Colors / theme** – Adjust Tailwind classes.

---

## **License**

MIT License © CodesWithSubham

