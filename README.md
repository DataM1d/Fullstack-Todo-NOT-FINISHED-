🚀 Task Manager Pro: Full-Stack Monorepo
A professional grade, domain driven Task Management application built with the MERN stack (MongoDB, Express, React, Node.js).

🛠 Tech Stack
Frontend
React 18 (Functional Components, Hooks)

Vite (Build Tool)

CSS3 (Custom Properties, Flexbox/Grid, Dark Mode)

Axios (API Client)

Backend
Node.js & Express (RESTful API)

MongoDB & Mongoose (Data Modeling)

Cors (Cross Origin Resource Sharing)

🏗 Project Architecture
This project follows a Separation of Concerns (SoC) principle to ensure scalability:

Services Layer: Abstracted API calls using Axios instances to keep components "dumb."

Domain Hooks: Logic heavy hooks (useFilteredTodos) handle data transformation and filtering away from the UI.

Optimistic UI: State updates happen instantly on the client side with automatic rollback logic on server failure.

Monorepo Structure: Unified version control for both client and server logic.

📋 Key Features
✅ Real-time Stats: Dynamic tracking of completed vs. active tasks.

🌓 Smart Dark Mode: Persistent theme switching with CSS variables.

📂 Category Management: Dynamic task categorization with auto-generated color coding.

🗑 Bulk Actions: Single click "Clear Completed" using concurrent API requests.

📱 Responsive Design: Fully optimized for Desktop, Tablet, and Mobile.
