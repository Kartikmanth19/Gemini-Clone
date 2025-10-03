Gemini Chat 🪐💬

Gemini Chat is a modern, real-time chat application built with React, Vite, and Tailwind CSS. It enables users to communicate seamlessly with multiple chat rooms or direct messages. The app is responsive, fast, and designed for a smooth user experience.

Live Demo: [https://geminii-clone-kuvaka.netlify.app/]

Project Overview 🌟

Real-time messaging with multiple chat rooms or direct messages.

Responsive design for desktop and mobile devices.

Clean and intuitive interface for effortless navigation.

Implements features like throttling, pagination, infinite scroll, and form validation for better performance and user experience.

Setup and Run Instructions 💻
Clone the repository
git clone https://github.com/Kartikmanth19/Gemini-Clone.git
cd gemini-chat

Install dependencies
npm install
# or
yarn install
# or
pnpm install

Start the development server
npm run dev
# or
yarn dev
# or
pnpm dev


Open http://localhost:5173


 to see the app in action. The app auto-refreshes as you edit files.

Folder/Component Structure 🗂️
gemini-chat/
├─ public/                 # Static assets like images, favicon
├─ src/
│  ├─ components/          # Reusable React components
│  │  ├─ ChatBox/          # Main chat window
│  │  ├─ MessageList/      # Displays messages with pagination/infinite scroll
│  │  ├─ MessageInput/     # Form for sending messages
│  │  └─ Header/           # App header/navbar
│  ├─ pages/               # App pages (if routing implemented)
│  ├─ context/             # React Context API or state management
│  ├─ utils/               # Utility functions (throttling, validation, etc.)
│  ├─ hooks/               # Custom hooks
│  └─ styles/              # Tailwind CSS configurations and custom styles
├─ package.json
└─ README.md


Explanation:

components/: Reusable UI pieces for modularity.

context/: State management for user sessions and chat data.

utils/: Contains helper functions for throttling, validation, and pagination.

hooks/: Custom hooks to handle API calls, infinite scrolling, or other logic.

Features Implementation 🔧
Throttling ⚡

Ensures input events (like typing) or API calls are limited to prevent performance issues.

Implemented using lodash.throttle or custom throttle functions in utils/.

Pagination 📄

Messages are loaded in batches instead of all at once to improve performance.

Allows users to navigate between pages or load older messages dynamically.

Infinite Scroll ⬇️

Automatically loads more messages as the user scrolls up in the chat window.

Implemented with scroll event listeners and a combination of throttling to prevent excessive API calls.

Form Validation ✅

Ensures messages and input fields meet required criteria before submission.

Implemented with React state and utility functions in utils/validation.js.

Deployment 🌐

I have deploy Gemini Chat on platforms like:

Netlify Live Link :- https://geminii-clone-kuvaka.netlify.app/
