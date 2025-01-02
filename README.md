# MultiversX Escrow DApp

This project is a decentralized escrow application built using the [MultiversX SDK](https://docs.multiversx.com) for managing secure transactions on the MultiversX blockchain. The application provides a platform for users to escrow assets safely, ensuring that both parties in a transaction can trust the process.

## Features

- **Escrow Management**: Secure transactions between buyers and sellers.
- **MultiversX Blockchain Integration**: Uses the MultiversX SDK for seamless integration with the MultiversX blockchain.
- **React & Material Tailwind UI**: Provides a responsive user interface for interaction.
- **Formik & Yup**: Forms and validation for better UX.

## Project Setup

To get started with the development of the MultiversX Escrow DApp, follow these steps:

### Prerequisites

- Node.js (version 18.x or above)
- npm (version 8.x or above)

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd mx-escrow-tutorial-dapp
   ```

2. Install dependecies:

   ```bash
   npm install
   ```

3. Run the development server:
   ```bash
   npm run dev
   ```

### Directory Structure

```bash
.
├── src/                  # Source files for the DApp
│   ├── components/       # React components
│   ├── config/           # Service URL set-ups
│   ├── helpers/          # Helper functions
│   ├── hooks/            # Hooks
│   ├── pages/            # Pages
│   ├── App.tsx           # Main application file
│   └── main.tsx         # Entry point for React
├── public/               # Static assets like images
├── tailwind.config.js    # Tailwind CSS configuration
├── vite.config.ts        # Vite build configuration
├── package.json          # Project dependencies and scripts
└── tsconfig.json         # TypeScript configuration
```
