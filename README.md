# sql-gpt-frontend: Next.js User Interface

This is the Next.js frontend application for the `sql-gpt` project. It provides the user interface for inputting natural language prompts and displaying the generated SQL queries from the backend API.

## 🛠️ Local Development Setup

### Prerequisites

- **Node.js** (LTS recommended)
- **npm**, **yarn**, or **pnpm** (Node package manager)

### Setup Steps

#### 1. Navigate to the Frontend Directory

Ensure you are inside the `sql-gpt/frontend` folder.

```bash
cd sql-gpt/frontend
```

#### 2. Install Dependencies

Install the necessary Node.js packages:

```bash
npm install
# or yarn install
# or pnpm install
```

#### 3. Configure Environment Variables

Create a file named `.env.local` in this directory. This file should contain configuration specific to the frontend, primarily the URL of the backend API.

```bash
# Example .env.local file content
NEXT_PUBLIC_API_URL=http://localhost:8000
# Add any other environment variables used by the frontend here
```

> **Note:** Next.js requires the `NEXT_PUBLIC_` prefix for variables to be accessible in the browser.

## 🏃 Running the Development Server

### 1. Start the Development Server

Run the Next.js development script:

```bash
npm run dev
# or yarn dev
# or pnpm dev
```

### 2. Access the Application

The application will automatically open in your browser, typically at `http://localhost:3000`. The console will provide the exact URL. Changes to the source files will be reflected automatically via hot-reloading.

---

## 📁 Project Structure

```
frontend/
├── app/                 # Next.js App Router pages and layouts
├── components/          # Reusable React components
├── public/              # Static assets
├── styles/              # Global styles and CSS modules
├── .env.local           # Environment variables (create this file)
├── package.json         # Project dependencies
├── next.config.js       # Next.js configuration
└── README.md            # This file
```

## 🏗️ Building for Production

To create an optimized production build:

```bash
npm run build
npm run start
```

The production server will run on `http://localhost:3000` by default.

## 🧪 Testing

```bash
# Run tests (if configured)
npm run test

# Run linting
npm run lint
```

## 🎨 Features

- **Natural Language Input**: Intuitive interface for entering SQL queries in plain English
- **Real-time Generation**: Live SQL query generation powered by AI
- **Syntax Highlighting**: Beautiful code display for generated SQL
- **Responsive Design**: Works seamlessly on desktop and mobile devices

## 🤝 Contributing

Contributions are welcome! Please ensure your code follows the project's style guidelines and includes appropriate tests.

## 📄 License

See LICENSE file for details.
