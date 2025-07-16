NETS - Neuro Engineering and Training School
Welcome to the official repository for the Neuro Engineering and Training School (NETS) web application. This project is a modern web application built with a fast, efficient, and type-safe stack, designed to provide a seamless user experience.
This project was bootstrapped from a Vite + React + TypeScript starter, providing a solid foundation for rapid development and a fantastic developer experience.
✨ Core Technologies
This project is built using a curated set of modern web technologies to ensure performance, scalability, and code quality:
Framework: React 18 for building dynamic and responsive user interfaces.
Build Tool: Vite for a lightning-fast development server and optimized production builds.
Language: TypeScript for static typing, leading to more robust and maintainable code.
Styling: Tailwind CSS for a utility-first CSS framework that enables rapid UI development.
Backend as a Service: Supabase for handling backend functionalities like authentication, databases, and storage.
Linting: ESLint with TypeScript ESLint to enforce consistent code style and prevent common errors.
Icons: Lucide React for a beautiful and consistent set of open-source icons.
UI Components: Includes libraries like react-day-picker for rich date selection.
🚀 Getting Started
To get a local copy up and running, follow these simple steps.
Prerequisites
Make sure you have Node.js (version 18.x or higher) and npm installed on your machine.
Installation
Clone the repository
Generated sh
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
Use code with caution.
Sh
Install NPM packages
This will install all the necessary dependencies listed in package.json.
Generated sh
npm install
Use code with caution.
Sh
Set up Environment Variables
This project uses Supabase for its backend. You will need to create a .env file in the root of the project and add your Supabase project credentials.
Create a file named .env and add the following:
Generated code
VITE_SUPABASE_URL=your-supabase-project-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
Use code with caution.
You can find these keys in your Supabase project's API settings.
🛠️ Available Scripts
In the project directory, you can run the following commands:
npm run dev
This command starts the Vite development server. Open http://localhost:5173 (or the port shown in your terminal) to view the application in your browser. The page will reload automatically if you make edits.
npm run build
This builds the app for production to the dist folder. It correctly bundles React in production mode and optimizes the build for the best performance.
npm run lint
This command runs ESLint to analyze the codebase for potential errors and style issues based on the rules defined in eslint.config.js.
npm run preview
This command serves the production build from the dist folder locally. It's a great way to check if the production build works as expected before deploying.
🎨 Styling and Configuration
Tailwind CSS: Configuration is located in tailwind.config.js. You can customize the theme, add new utilities, and more.
PostCSS: Used for processing Tailwind CSS and Autoprefixer. The configuration can be found in postcss.config.js.
ESLint: Our linter is configured in eslint.config.js to ensure code quality and consistency across the project. It includes rules for TypeScript, React Hooks, and React Refresh.
TypeScript: The project uses separate TypeScript configurations for the application source code (tsconfig.app.json) and the Node.js environment files (tsconfig.node.json).
