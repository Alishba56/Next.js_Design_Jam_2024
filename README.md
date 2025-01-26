# Honest Bazar

Welcome to **Honest Bazar**, a general e-commerce platform created as part of a marketplace hackathon project. This platform allows users to explore, browse, and purchase products seamlessly. The focus of Honest Bazar is on delivering a smooth user experience, secure transactions, and a robust design that scales.

## Project Overview
Honest Bazar is built to demonstrate:
- A fully functional e-commerce platform.
- Modern UI/UX design principles.
- Scalable architecture for a general marketplace.

## Features
- User authentication (Sign Up, Log In, Log Out).
- Product browsing with categories and search functionality.
- Cart and checkout process.
- Integration with payment gateways (mock implementation for hackathon).
- Responsive design for both desktop and mobile devices.

## Tech Stack
- **Frontend**: React, TypeScript, CSS
- **Backend**: Node.js, Express
- **Database**: Sanity
- **Hosting**: Vercel (Frontend) and Render (Backend)

## Folder Structure
```
.
├── /src                # Source code for the application
│   ├── /components    # Reusable UI components
│   ├── /pages         # Main pages of the app
│   ├── /styles        # Global and component-specific styles
│   └── /utils         # Helper functions and utilities
├── /documents          # Reports and project documentation
├── .env                # Environment variables (not included in the repo)
├── README.md           # Project summary and setup instructions
└── package.json        # Project dependencies and scripts
```

## Setup and Deployment
### Prerequisites
Ensure you have the following installed:
- Node.js (v16+)
- npm or yarn
- Git

### Steps to Run Locally
1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project folder:
   ```bash
   cd honest-bazar
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Add environment variables:
   - Create a `.env` file in the root directory.
   - Add the necessary variables (e.g., database URL, API keys).
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Access the app at `http://localhost:3000`.

### Deployment
- The application is deployed on **Vercel** for the frontend and **Render** for the backend.
- Access the staging environment at: [Staging Environment Link](#) (Replace `#` with the actual link).

## Documentation
All project-related documents, including reports and detailed documentation, can be found in the `/documents` folder.

## Acknowledgments
Special thanks to the hackathon organizers and teammates for their support and feedback.

---
For any issues or feedback, please raise an issue or reach out to us directly.
