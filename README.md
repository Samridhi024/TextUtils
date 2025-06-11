# ✨ Text Utility App

A simple and powerful React-based application to **analyze and manipulate text efficiently**. This tool allows users to:

- Convert text to **UPPERCASE** or **lowercase**
- **Remove extra spaces**
- **Count words and characters**
- View **live preview**
- Toggle between **light and dark mode**

All within a clean, responsive UI.

## 🚀 Getting Started

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/text-utility-app.git
````

Navigate to the project directory:

```bash
cd text-utility-app
```

Install dependencies:

```bash
npm install
```

### ▶️ Start the App

To start the development server:

```bash
npm start
```

Runs at: [http://localhost:3000](http://localhost:3000)
The page reloads automatically on code changes.

---

## 🧪 Running Tests

```bash
npm test
```

Launches the test runner in interactive watch mode.

---

## 🛠️ Build for Production

```bash
npm run build
```

Creates an optimized production build in the `build` folder.

---

## ⚙️ Customize Configuration

To take full control of the build tools (Webpack, Babel, ESLint, etc.):

```bash
npm run eject
```

> ⚠️ **Note**: This action is permanent and cannot be undone.

---

## 🌐 Learn More

* [React Documentation](https://reactjs.org/)
* [Create React App Docs](https://create-react-app.dev/)
* [Deployment Guide](https://create-react-app.dev/docs/deployment/)
* [Code Splitting](https://create-react-app.dev/docs/code-splitting/)
* [Progressive Web App](https://create-react-app.dev/docs/making-a-progressive-web-app/)

---

## 📚 How I Built This

I began learning React by exploring the official [React documentation](https://reactjs.org/docs/getting-started.html), practicing small UI components, and watching beginner-friendly tutorials. To apply what I learned, I built this app using:

### 🔧 Tools & Technologies Used

* **React** (with Functional Components)
* **React Router v6** – for page navigation
* **Bootstrap** – for responsive UI styling
* **JSX** – for structuring UI components

### ⚙️ Key Concepts Implemented

* **Functional Components**:

  * `Navbar` – navigation bar
  * `TextForm` – text analyzer
  * `About` – app overview
  * All imported and used in `App.js`

* **State Management (`useState`)**:
  Used to toggle between light and dark mode:

  ```js
  const [mode, setMode] = useState("light");
  ```

* **Props**:
  Props were passed from `App.js` to components like:

  ```jsx
  <Navbar title="TextUtils" mode={mode} toggleMode={toggleMode} />
  ```

* **Conditional Rendering**:
  Background color changes dynamically based on the selected mode.

* **Routing with React Router v6**:

  ```jsx
  <Routes>
    <Route path="/about" element={<About />} />
    <Route path="/" element={<TextForm heading="Enter the text to analyse:" mode={mode} />} />
  </Routes>
  ```

* **Bootstrap Integration**:
  Bootstrap styles were added globally:

  ```js
  import 'bootstrap/dist/css/bootstrap.min.css';
  ```

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

