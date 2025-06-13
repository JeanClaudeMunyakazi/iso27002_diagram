# ISO/IEC 27002:2022 Diagram – Responsive HTML Visualization

This project provides a responsive, dark-mode HTML/CSS visualization of the **ISO/IEC 27002:2022** standard, showcasing all 93 security controls across the four main domains:

* **Organizational Controls** (37)
* **People Controls** (8)
* **Physical Controls** (14)
* **Technological Controls** (34)

Designed for easy visual reference, this layout can be integrated across multiple platforms like WordPress blogs, Microsoft SharePoint sites, Power Pages, and Microsoft Teams Tabs.

---

## Features

*  **ISO/IEC 27002:2022 compliant** visualization
*  Fully **dark-mode** interface for accessibility
*  Responsive layout optimized for **Desktop**, **Tablet**, and **Mobile**
*  Clean separation of domains, controls, and visual legends
*  Easy to extend with JavaScript filtering or interactivity (future support)

---

##  Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/JeanClaudeMunyakazi/iso27002_Diagram.git
```

### 2. Open the File

Simply open `iso27002_Diagram.html` in any modern browser.

---

##  Responsive Design

| Device  | Behavior                        |
| ------- | ------------------------------- |
| Desktop | Two-column layout, full display |
| Tablet  | Stack adjusts for touch layouts |
| Mobile  | Single-column vertical layout   |

---

##  Platform Integration Guide

###  WordPress (Self-Hosted / Elementor)

* Add an **HTML widget** in your Elementor layout
* Paste the entire HTML code into the widget
* OR upload the `.html` file to your server and link via button:

```html
<a href="/assets/iso27002_Diagram.html" target="_blank">Open Diagram</a>
```

###  Microsoft SharePoint (Modern Site)

**Option A – Upload & Link:**

1. Upload `iso27002_Diagram.html` to **Site Assets**
2. Create a modern **Page**
3. Add a **File Viewer** or **Quick Links** web part pointing to the file

**Option B – Embed (Requires Admin Config):**

* Host the `.html` on an external site (e.g., GitHub Pages)
* Use an `iframe` In a SharePoint embed web part:

```html
<iframe src="https://yourhost.com/iso27002_Diagram.html" width="100%" height="800"></iframe>
```

###  Microsoft Power Pages

* Upload the HTML as a **Web File**
* Use a **Web Page** or **Web Template** to serve the content
* Useful for internal compliance dashboards and ISO portals

###  Microsoft Teams Tabs

* Add the hosted or SharePoint-linked file as a **Website Tab** or **SharePoint Tab**
* Embed inside channels like "IT Security" or "Governance"

---

## 📸 Screenshots

* Coming soon in **`/assets/screenshots`** folder.*

---

##  License

This project is licensed under the MIT License. You are free to use, modify, and distribute for educational and non-commercial use.

---

##  Contributing

Feel free to fork and submit pull requests to enhance functionality, add interactivity, or translate control labels.

---

## 🔗 Links

* [ISO/IEC 27002:2022 Overview Blog](https://munyakazi.org/professional-blog/it-security-management-framework/)
* [Live Demo](https://yourdomain.com/path/iso27002_Diagram.html)
* [Author Portfolio](https://munyakazi.org)
