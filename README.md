# Frontend-of-Blogging-Platform
to used this application used "npm start" in your terminal.
Approach to Solve the Problem Statement
Frontend (React)
Component-Based Architecture: Created reusable UI components (PostCard, RichTextEditor, Navbar)

State Management: Used React hooks (useState, useEffect, useContext) for state management

Routing: Implemented protected routes using React Router

Rich Text Editing: Integrated CKEditor for content creation

Responsive Design: Built with Tailwind CSS for mobile-first responsiveness

Error Handling: Comprehensive error states and loading indicators

AI Assistance in Development
How I Used AI Tools:
Code Generation:

Used GitHub Copilot for boilerplate code (component structures, API routes)

Generated sample database schemas with ChatGPT

Debugging Assistance:

Diagnosed "Cannot read properties of undefined" errors with AI help

Fixed CKEditor integration issues with AI suggestions

Code Optimization:

Improved React performance with AI-recommended optimizations

Enhanced error handling patterns

Documentation:

Generated initial README structure

Created code comments and JSDocs

Learning:

Explained complex concepts (JWT auth, Sequelize associations)

Suggested modern React patterns

Frontend Setup
Clone the repository:

bash
git clone [frontend-repo-url]
cd client
Install dependencies:

bash
npm install
Configure environment:

Create .env file:

REACT_APP_API_URL=http://localhost:5000
Start development server:

bash
npm start

Development Scripts

Frontend
npm start: Start development server

npm build: Create production build

npm test: Run tests

Frontend
client/
├── public/       # Static assets
├── src/
│   ├── components/  # Reusable components
│   ├── pages/       # Page components
│   ├── context/     # Auth context
│   ├── services/    # API services
│   ├── styles/      # Global styles
│   ├── App.js       # Main component
│   └── index.js     # Entry point
└── package.json
