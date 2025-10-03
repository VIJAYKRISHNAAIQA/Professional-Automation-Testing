
---

````markdown
## 🧪 Automation Testing Practice Web Page  
## 🎯 Professional Edition | Ideal for Selenium, Playwright, Cypress, Puppeteer & More

---

## 📌 Overview

This project is a fully interactive, responsive HTML-based **automation testing playground** for developers and QA engineers. It's designed to simulate **real-world UI test cases** — from simple form handling to complex window/tabs, dynamic DOM interactions, and AJAX behaviors.

🧑‍💻 Whether you're an SDET, test automation engineer, or learning browser automation tools, this page will give you:

✅ Locator practice (ID, name, class, XPath, CSS, link text, data-*)  
✅ Complex test scenarios (AJAX, modal nesting, iFrames, shadow DOM)  
✅ Hands-on features to sharpen your automation skills!

---

## 🗂️ Folder Structure


/automation-testing-practice/
├── index.html                  # Main HTML page
├── /css/
│   └── styles.css              # UI styling (cards, transitions, layout)
├── /js/
│   └── scripts.js              # JS functionality (modals, alerts, AJAX)
├── /assets/
│   ├── logo.png                # Placeholder logo
│   └── sample-file.txt         # File upload testing
├── /docs/
│   └── README.md               # This readme
````

---

## 🚀 Quick Start

### 🧰 Requirements:

* Browser (Chrome, Edge, Firefox)
* (Optional) Git for cloning

### 🛠️ Setup Instructions

```bash
# 1. Clone the repository
git clone https://github.com/your-username/automation-testing-practice.git

# 2. Navigate into the folder
cd automation-testing-practice

# 3. Open the project
start index.html  # Or open manually in browser
```

✅ No server, npm, or build tools required — pure HTML/CSS/JS!

---

## 📚 Features by Level

### 🔹 **BASIC LEVEL** — *Beginner Automation Testing*

| Feature                          | Details                           |
| -------------------------------- | --------------------------------- |
| 🧾 Text Input Fields             | With `id`, `name`, `class`        |
| ✅ Checkboxes & Radio Buttons     | For selection testing             |
| 🌍 Dropdown Select               | With `id="country-select"`        |
| 📝 Textarea                      | With char limits and placeholders |
| 🔗 Link Text Practice            | Full and partial link match       |
| 🧪 Required & Disabled Fields    | HTML5 validation, tooltips        |
| 📩 Form Submission & Preview Box | Output appears dynamically        |
| 🫥 Hidden Element                | Appears on hover                  |

---

### 🟡 **MEDIUM LEVEL** — *Window, Tabs, Dialogs*

| Feature                | Details                                              |
| ---------------------- | ---------------------------------------------------- |
| 🪟 Open New Window     | Simulate window switching (Selenium `windowHandles`) |
| 🧭 Open New Tab        | `target="_blank"` simulation                         |
| ⚠️ JavaScript Alerts   | `alert()`, `confirm()`, `prompt()`                   |
| 🪟 Custom Modal Dialog | With close button, overlay, ESC key handling         |
| 🔁 Nested Modal        | Modal inside a modal                                 |
| 🧩 iFrame Interaction  | Embedded interactive content                         |
| 📊 Data Table          | Rows, IDs, pagination controls                       |

---

### 🔴 **ADVANCED LEVEL** — *Dynamic & Complex Automation*

| Feature                     | Details                                   |
| --------------------------- | ----------------------------------------- |
| ⏱️ AJAX Simulation          | With `setTimeout()` and content injection |
| 🫣 Hidden on Load           | Elements revealed on scroll or hover      |
| 🆔 Dynamic IDs              | Modal with `id="modal-{timestamp}"`       |
| 🔄 Attribute Toggle         | Enable/disable or readonly via JS         |
| 🧩 Shadow DOM (optional)    | Hard-to-access locators                   |
| 📤 File Upload + Validation | Show uploaded file info                   |
| 🧲 Drag & Drop Zone         | Visual dropzone with dynamic feedback     |
| 🌐 Nested iFrame with Form  | Complex iFrame interaction                |

---

## 🧩 Locator Strategy Cheat Sheet

| Locator Type       | Example                       |
| ------------------ | ----------------------------- |
| `id`               | `id="username"`               |
| `name`             | `name="email"`                |
| `class`            | `class="input-password"`      |
| `link text`        | `Help Page`                   |
| `partial link`     | `Help`                        |
| `CSS selector`     | `div.panel > button.submit`   |
| `XPath`            | `//div[@class='card']//input` |
| `data-* attribute` | `data-test-id="login-button"` |

> 🎯 Perfect for building selector-based automation frameworks.

---

## 🎨 UI/UX Highlights

* 🎛️ **Dark / Light Mode Toggle**
* 📦 **Card-Based Layout** per Level
* 📍 **Sidebar Navigation** with anchor links
* 🎨 **CSS Transitions & Hover Effects**
* 🏷️ **Bootstrap-style Badges** for Section Types:

  * 🔹 Basic — Blue
  * 🟡 Medium — Yellow
  * 🔴 Advanced — Red

---

## 🔐 Bonus Section — Login Simulation

🧪 **Mock Login**:

| Field    | Value      |
| -------- | ---------- |
| Username | `admin`    |
| Password | `admin123` |

✔️ Displays **success or error** messages based on credentials — ideal for positive & negative test cases.

---

## 🧪 Compatible Automation Tools

| Tool          | Compatible |
| ------------- | ---------- |
| ✅ Selenium    | ✔️         |
| ✅ Playwright  | ✔️         |
| ✅ Cypress     | ✔️         |
| ✅ Puppeteer   | ✔️         |
| ✅ TestCafe    | ✔️         |
| ✅ WebdriverIO | ✔️         |

> Also great for manual inspection using browser DevTools!

---

## 👨‍💻 Tech Stack

* `HTML5` — Semantic, accessible structure
* `CSS3` — Grid, Flexbox, transitions
* `JavaScript` — DOM manipulation, modals, events
* 🎨 Clean UI + Developer-friendly layout

---

## 🤝 Contributing

Have ideas to improve the test lab?

1. Fork this repo
2. Create a new branch: `feature/my-enhancement`
3. Submit a PR with your feature/fix
4. Tag an issue or describe your update

🙌 All contributors are welcome — testers, devs, and learners!

---

## 📄 License

Use freely for personal, academic, or internal company training.

---

## 👤 Author

**Maintainer:** Vijay Krishna (https://github.com/your-profile)
📫 Contact: `your.email@example.com` (or GitHub issues)

---

## ⭐ Support the Project

If you find this helpful for testing or learning:

👍 Star this repo
🍴 Fork it
💬 Share with your QA/dev team
🚀 Use it in test automation demos

---

## 🔗 GitHub Pages Deployment (Optional)

You can deploy this project as a **live test site** using [GitHub Pages](https://pages.github.com/):

1. Push your code to a GitHub repo
2. Go to **Settings > Pages**
3. Choose:

   * Source: `main`
   * Folder: `/root`
4. Save & wait 30–60 seconds

You'll get a public URL like:

```
https://your-username.github.io/automation-testing-practice/
```

🧪 Perfect for live automation script testing!

---

### 🔻 Download This Project as ZIP

Or download a bundled ZIP with:

✅ `index.html`
✅ `/css/styles.css`
✅ `/js/scripts.js`
✅ `/assets/`
✅ `/docs/README.md`

📦 [Click here to download the ZIP](#) 

