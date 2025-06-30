````markdown
# Apex Bank Landing Page

A modern, responsive Angular landing page for Apex Bank, featuring:

- A dynamic header with bank name & tagline  
- Split-screen “About” section & login form  
- Standalone Angular components (Header, Login, About, Team, Support, Footer)  
- SSG/Prerendering–ready setup  
- Clean, corporate styling with CSS animations  
- Fully responsive for desktop & mobile  

---

## 👀 Demo

![Landing Page Screenshot](docs/screenshot.png)  
![image](https://github.com/user-attachments/assets/3d8e684c-5a8c-407e-9d8c-94e2d1be1fc4)


---

## 🚀 Quick Start

### Prerequisites

- Node.js ≥ 16  
- npm ≥ 8  
- Angular CLI (optional, for global use):  
  ```bash
  npm install -g @angular/cli
````

### Installation

1. **Clone the repo**

   ```bash
   git clone https://github.com/your-org/apex-bank.git
   cd apex-bank
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Serve locally**

   ```bash
   npm run dev
   # or
   ng serve --open
   ```

   Your browser should open at `http://localhost:4200/`.

---

## 📁 Project Structure

```
falana-bank/
├─ src/
│  ├─ app/
│  │  ├─ header/     # HeaderComponent (bank name/tagline)
│  │  ├─ login/      # LoginComponent (split-page login)
│  │  ├─ about/      # AboutComponent (bank description)
│  │  ├─ team/       # TeamComponent (flip-card profiles)
│  │  ├─ support/    # SupportComponent (contact info)
│  │  ├─ footer/     # FooterComponent (footer links)
│  │  ├─ app.ts      # Root standalone component
│  │  ├─ app.html
│  │  └─ app.css
│  ├─ assets/        # Images, illustrations, icons
│  ├─ styles.css     # Global styles
│  ├─ main.ts        # Bootstrap file
│  └─ index.html
├─ angular.json
├─ package.json
└─ README.md
```

---


* **Animations**
  All components use CSS keyframes; feel free to adjust durations or easing functions.

---

## 🙋‍♂️ Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/my-feature`)
3. Commit your changes (`git commit -m "Add feature"`)
4. Push to your branch (`git push origin feature/my-feature`)
5. Open a Pull Request

Please adhere to the existing code style and run `npm run lint` & `npm test` before submitting.

---

## 📄 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

```
```
