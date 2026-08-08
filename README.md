# 🎨 Pengenalan & Panduan Instalasi Sass

![Sass Header](https://img.shields.io/badge/Sass-CC6699?style=for-the-badge&logo=sass&logoColor=white)
![CSS3 Header](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

Welcome to the basic guide to **Sass** (Syntactically Awesome Style Sheets)! This documentation is designed to help you understand the basic concepts of Sass and get started with the installation process quickly and easily.

---

## 📌 What is Sass?

**Sass** is a CSS preprocessor that adds extra power and functionality to standard CSS. With Sass, you can use programming-like features such as **variables**, **nesting**, **mixins**, **functions**, and **modules** that are not available in standard CSS.

### Why Use Sass?
* **Code Efficiency:** Reduces repetitive code (*DRY - Don't Repeat Yourself*).
* **Ease of Maintenance:** File structure is more organized and easier to manage for large-scale projects.
* **Compatibility:** All Sass code is compiled into standard CSS, making it readable by all browsers.

---

## 🚀 Installation Guide

Sass requires Node.js to run from the command line (*terminal*).

### Prerequisites
Make sure **Node.js** and **npm** are installed on your device. Check via the terminal:
```bash
node -v
npm -v

```
Step 1: Installing Sass (Globally)
Run the following command in the terminal to install Dart Sass globally on your system:
```
npm install -g sass
```
Installation Verification:
Make sure Sass is installed correctly by checking its version:
```
sass --version
```
Step 2: Compiling Sass Files to CSS
Sass uses the .scss or .sass file extensions. To convert Sass files to standard CSS:
Single Build
```
sass style.scss style.css
```
Watch Mode
This option is highly recommended during the development process. Sass will automatically compile every time you save changes to a .scss file:
```
sass --watch style.scss style.css
```
If you're using a folder structure (e.g., src/scss and dist/css):
```
sass --watch src/scss:dist/css
```
Sass brings programming-language-style features to standard CSS. Here are the main features of Sass and their functions:
1. Variables<br>
Store values such as colors, font sizes, or spacing so they can be reused and easily modified in one place.
2. Nesting
Writing CSS selectors in a nested manner that follows the HTML hierarchy. This makes the code much cleaner and easier to read.
3. Mixins & @include
Store a set of frequently reused CSS properties (such as flexbox layouts, box-shadow, or media queries) and accept parameters or arguments.
4. Partials & Modules (@use / @import)
Break CSS files down into small pieces (called partials, usually prefixed with an underscore, such as _variables.scss) and then combine them into a single main file.
5. Extend / Inheritance (@extend)
Inherits all attributes from one selector to another without having to rewrite the code.
6. Functions & Control Directives (Functions, Conditions, Loops)
Sass supports programming logic such as creating custom functions, conditional statements (@if, @else), and loops (@for, @each).

📚 Licenses & Contributions
This project is open to everyone. Feel free to fork it, submit a pull request, or provide feedback via the issues tab.

---

<FollowUp label="Ingin penjelasan lebih detail mengenai perbedaan format .scss dan .sass?" query="Bisa jelaskan perbedaan antara format ekstensi .scss dan .sass dalam Sass?"/>
