# SCSS: Trillo Project

### 📚 Overview

This project is a responsive web layout made using **SCSS** and **Flexbox**. The project focuses on creating modular, reusable styles with SCSS, following a well-organized folder structure for maintainability and scalability.

### 🚀 Features:

- **Modular SCSS Architecture**: Organized using partials like `_base.scss`, `_components.scss`, and `_layout.scss` for better code management.
- **Responsive Design**: Built with Flexbox to ensure the layout adapts seamlessly across different screen sizes.
- **Reusable Components**: Designed with flexibility in mind, making it easy to extend or modify.
- **Clean and Maintainable Code**: Utilizes SCSS variables, BEM (Block Element Modifier) methodology, mixins, and nesting for efficient styling.

### 💻 Technologies Used:

- **SCSS (Sassy CSS)**: For advanced CSS features like variables, nesting, and mixins.
- **Flexbox**: To create flexible, responsive layouts without the need for float or positioning hacks.
- **HTML5**: For semantic and structured markup.

### Prerequisites:

Make sure you have the following installed:

- **Node.js**: (https://nodejs.org/) - Required for installing dependencies.
- **npm**: Comes with Node.js, used to manage project dependencies.
- **Sass**: Install Sass globally using the command:
  ```bash
  npm install -g sass
  ```

### 📂 Project Structure

```bash
scss-flexbox-project/
├── css/
├── img/
├── node_modules/
├── sass/
│   ├── _base.scss
│   ├── _components.scss
│   ├── _layout.scss
│   └── main.scss
├── index.html
├── package-lock.json
├── package.json
└── README.md
```

### 📸 Preview

![Project Screenshot](https://github.com/user-attachments/assets/268ea516-7c63-4bf1-a8d8-8ae9dc1b5169)

### 💾 How to Run the Project

### 1️⃣ **Clone the repository:**

```bash
git clone https://github.com/Caiko/trillo.git
```

### 2️⃣ **Navigate to the project folder:**

```bash
cd trillo
```

### 3️⃣ **Install dependencies:**

```bash
npm install
```

### 4️⃣ **Fire it up:**

```bash
npm start
```

**Open `index.html` in your browser** to see the layout.

### SCSS Architecture

- **`_base.scss`**: Contains basic styles like resets, typography, and default settings.
- **`_components.scss`**: Manages all reusable UI components.
- **`_layout.scss`**: Defines the page structure, grid systems, and Flexbox utilities.
- **`main.scss`**: The main SCSS file that imports all partials.
