# Sign-up Form | The Odin Project 🌲

A responsive and visually appealing Sign-up Form built as part of [The Odin Project](https://www.theodinproject.com/) curriculum. This project focuses on modern CSS layouts, semantic HTML5, and client-side form validation.

## 🎯 Objective
The main goal of this project was to build a functional sign-up form matching a provided design, with a strong emphasis on:
- Pixel-perfect implementation from a reference image.
- Splitting the screen layout using CSS Flexbox.
- Providing visual feedback for form validation (valid/invalid states).
- Implementing a clean and scalable CSS architecture.

## 🛠️ Technologies & Tools
- **HTML5:** Semantic structure (`<main>`, `<aside>`, `<section>`, `<header>`).
- **CSS3:** - Flexbox for responsive layouts and splitting the screen (sidebar vs. form area).
  - Custom local fonts (`@font-face` with `.otf` files).
  - Pseudo-classes for form validation (`:focus:invalid`, `:focus:valid`).
  - Modular Architecture (Base, Components, and Modules organized within a single file).

## 💡 What I Learned
Throughout this project, I solidified several core web development concepts:
1. **Semantic HTML & Accessibility:** Structuring the document correctly using `<aside>` for the visual branding and `<main>` for the core content. Ensuring every `<input>` has a properly linked `<label>`.
2. **Background Images vs. Image Tags:** Understanding when to use `background-image` in CSS (like the sidebar leaf background) to allow text and logos to seamlessly overlay the image, rather than fighting with the `<img>` tag in HTML.
3. **CSS Architecture:** Organizing CSS mentally into Base (resets, typography), Modules (aside, main), and Components (forms, buttons) to keep the code maintainable.
4. **Form Validation UX:** Enhancing user experience by linking CSS pseudo-classes to HTML validation