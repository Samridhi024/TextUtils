✨ Text Utility App
A simple and powerful React-based application to analyze and manipulate text efficiently. This tool allows users to convert text to uppercase/lowercase, remove extra spaces, count words/characters, and more — all in a clean, responsive UI.

🚀 Getting Started
This project was bootstrapped with Create React App.

📦 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/text-utility-app.git
Navigate to the project directory:

bash
Copy
Edit
cd text-utility-app
Install dependencies:

bash
Copy
Edit
npm install
▶️ Start the App
To start the development server:

bash
Copy
Edit
npm start
The app runs on: http://localhost:3000
The page reloads automatically on code changes.

🧪 Running Tests
bash
Copy
Edit
npm test
Launches the test runner in interactive watch mode.

🛠️ Build for Production
bash
Copy
Edit
npm run build
Creates an optimized production build in the build folder.

⚙️ Customize Configuration
To take full control of the build tools (Webpack, Babel, ESLint, etc.):

bash
Copy
Edit
npm run eject
⚠️ Note: This action is permanent and cannot be undone.

🌐 Learn More
React Documentation

Create React App Docs

Deployment Guide

Code Splitting

Progressive Web App

📸 Features
Convert text to UPPERCASE or lowercase

Clear text input

Remove extra spaces

Word & character count

Live preview of your content

Toggle between light and dark mode

📚 How I Built This
I began learning React by exploring the official React documentation, practicing small UI components, and watching beginner-friendly video tutorials. To solidify my understanding, I built this project using functional components, state management with hooks, and routing.

🔧 Tools & Technologies Used
React (with Functional Components)

React Router v6 for page navigation

Bootstrap for styling and responsive layout

JSX for UI rendering and component logic

⚙️ Key Concepts Implemented
Functional Components:
I created custom reusable components like:

Navbar – for the top navigation bar

TextForm – for text analysis operations

About – to describe the purpose of the app

These components are imported and rendered in the main App.js file.

State Management using useState:
Used to handle dark mode toggle:
const [mode, setMode] = useState("light");
Props:
Props were passed from App.js to components like Navbar and TextForm to control behavior and appearance:
<Navbar title="TextUtils" mode={mode} toggleMode={toggleMode} />
Conditional Rendering:
Dynamically changed the background color of the page based on the selected mode.

Routing with React Router v6:
Enabled navigation between different pages (About & Home) using:
<Routes>
  <Route path="/about" element={<About />} />
  <Route path="/" element={<TextForm heading="Enter the text to analyse:" mode={mode} />} />
</Routes>


Bootstrap Integration:
Added responsive styling via Bootstrap: import 'bootstrap/dist/css/bootstrap.min.css';

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you'd like to change.

📄 License
This project is open source and available under the MIT License.

