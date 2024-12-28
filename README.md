# Socialix Client

## Overview

Socialix Client is the front-end application for the Socialix social networking platform. It is built using **React.js**, **Vite** for bundling and development server, **TypeScript** for static typing, **Redux** for state management, **React Router** for handling routing, and **OpenAPI2Aspida** for generating API client and models from Swagger JSON. The client-side interacts with the server-side via RESTful APIs and WebSocket connections for real-time features like chat.

## Technologies Used

- **React.js**: A popular JavaScript library for building user interfaces. React is used to build the component-based UI of the Socialix platform, allowing for efficient rendering and seamless user interactions.

- **Vite**: A next-generation front-end build tool that provides fast development builds and hot module replacement (HMR). Vite is used for bundling and optimizing the React application.

- **TypeScript**: A superset of JavaScript that introduces static typing. TypeScript helps with type safety and provides better development experience by catching errors at compile time.

- **Redux**: A predictable state container for JavaScript apps. Redux is used for managing global state, such as user authentication status, post data, and chat messages, across the application.

- **React Router**: A declarative routing library for React. React Router is used to navigate between different pages in the application, like the home page, user profile, groups, and post details.

- **Axios**: A promise-based HTTP client used to make API requests to the server, ensuring smooth communication between the client and server-side services (such as user authentication, post fetching, etc.).

- **Styled Components / CSS Modules (Optional)**: Used for styling components in a modular and maintainable way, promoting a clean separation of concerns between styles and logic.

- **OpenAPI2Aspida**: A tool that generates type-safe API clients and models from **Swagger** or **OpenAPI 3.x** specifications. This helps to automatically generate types and models for your API based on the server-side Swagger JSON, reducing the manual effort of creating API interfaces and ensuring consistency across the full stack.

## System Requirements

- **Node.js** (version 16.x or higher)
- **npm** (version 8.x or higher) or **yarn** (optional)
- **Vite** (install automatically via npm/yarn)
- A **browser** (Google Chrome, Firefox, or any modern browser)

## Setup Instructions

To get started with the Socialix client application, follow the steps below:

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Socialix-Project/socialix-client.git
   cd socialix
   ```
