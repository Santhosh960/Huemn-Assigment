# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.


About
Huemn Interactive Assignment is a React application created to showcase interactive UI/UX features (as part of an assignment). It was bootstrapped using Create React App.

Core Technologies:

React: A JavaScript library for building user interfaces. We will use it to create our application's structure out of reusable, isolated pieces of code called "components."

SCSS (Sass): A powerful extension of standard CSS. It will help us write more organized, reusable, and manageable styles for our components.

GSAP (GreenSock Animation Platform): A professional-grade JavaScript animation library. GSAP gives us precise control over every aspect of an animation (timing, sequencing, easing), making it the perfect tool for replicating the fluid and complex animations on the Chrome page.

Table of Contents
About

Features

Tech Stack

Getting Started

Prerequisites

Installation

Available Scripts

Folder Structure

Deployment

Future Enhancements

Contributing

License

Contact

Features
Responsive UI

Interactive components (buttons, forms, animations etc.)

Clean design and styling

Cross-browser compatibility

(You can list more specific features depending on what the app does: e.g. Navigation, Modal Dialogs, State Management, API Integration, etc.)

Tech Stack
Framework: React (Create React App)

Languages: JavaScript, HTML, CSS

Bundler / Build Tool: Webpack (via Create React App)

Deployment: Vercel



Folder Structure
Huemn_Interactive_Assignment/

├── public/

│ └── index.html

├── src/

│ ├── components/

│ ├── assets/

│ ├── styles/

│ ├── App.js

│ └── index.js

├── .gitignore

├── package.json

├── package-lock.json

└── README.md

Deployment
This project is deployed on Vercel.

After running npm run build, you can push to a Git branch connected to Vercel, or use Vercel’s CLI / dashboard to deploy.

Future Enhancements
Here are some ideas for improvements:

Add unit & integration tests

Improve accessibility (a11y)

Add theming / dark mode

Introduce state management (e.g. Redux or Context API, if the app scales)

Performance optimizations & code splitting

Contributing
Contributions are welcome! If you’d like to help out:

Fork the repository

Create a new branch (git checkout -b feature/my-feature)

Make your changes & test locally

Commit your changes (git commit -m 'Add some feature')

Push to your fork (git push origin feature/my-feature)

Open a Pull Request

Please ensure code style is consistent.
