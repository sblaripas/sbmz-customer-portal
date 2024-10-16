# 🌐 sbmz-customer-portal

Welcome to the **Standard Bank Mozambique Customer Portal**! This portal provides a secure and user-friendly way for customers to access a wide range of banking services online. Built with **Next.js** and modern web technologies, it offers multilingual support, seamless user experience, and various self-service features.

## 🚀 Features

### 🌍 **Internationalization**

- Supports multiple languages: 🇲🇿 Portuguese, 🇺🇸 English, 🇨🇳 Chinese.
- URLs are fully localized (e.g., `/en/pathnames` for English, `/pt/nomes-de-caminhos` for Portuguese).

### 💳 **Card Services**

- **Signature Card**: Get expert advice on investments, bespoke support from an Executive Banker, and 24/7 Signature Banking support.
- **Infinite Card**: Premium services with private banking, lounge access, and dedicated investment advice.

### 🛠️ **Self Service Links**

- **Internet Banking**: Access accounts, transactions, bill payments, and more.
- **Personal Account Opening**: Open or manage accounts entirely online.
- **Quiq Chat Banking**: Chat-based banking for quick and easy transactions.

### 🤖 **Bot Services**

- **National & International Transfers**: Manage transfers and receive proof instantly.
- **Statements and Balances**: Request account statements and view balances on-demand.

### ⚠️ **Error Handling**

- User-friendly error pages with actionable steps for recovery.

### 🏠 **Customer Dashboard**

- A customizable and easy-to-use dashboard to manage all services.

## 🛠️ **Tech Stack**

This portal is powered by a combination of modern web technologies:

- **Next.js** – A powerful React framework for server-rendered applications.
- **next-intl** – For seamless internationalization and localization of the app.
- **Radix UI** – Accessible and customizable UI components.
- **React Hook Form** – For smooth form handling and validation.
- **Tailwind CSS** – Utility-first CSS for rapid UI development.
- **Zod** – TypeScript-first schema validation.

## 📦 **Project Structure**

```bash
├── /app                 # Core application directory
│   ├── /[locale]        # Locale-based directories for i18n (internationalization)
│   │   ├── /cards       # Locale-specific card-related pages
│   │   ├── /dashboard   # Locale-specific dashboard-related pages
│   │   ├── /portal      # Locale-specific portal-related pages
│   │   └── /selfservice # Locale-specific self-service pages
│   │       └── /clientrequest  # Self-service client request feature
│   ├── /fonts           # Custom fonts used by the application
│   │   └── /BentonSans  # BentonSans font files
│   ├── /i18n            # Internationalization setup and configuration
│   └── /website         # Main website pages
├── /components          # Reusable UI components
│   ├── /layout          # Layout components (headers, footers, etc.)
│   └── /ui              # Small reusable UI components (buttons, cards)
├── /hooks               # Custom React hooks for shared logic
├── /lib                 # Library and helper functions
├── /messages            # Message and notification templates
├── /public              # Static assets accessible from the root URL
│   ├── /bots            # Assets for bots
│   ├── /cards           # Card-related images and assets
│   ├── /images          # General public images
│   └── /locales         # Language files for i18n
│       ├── /en          # English translations
│       └── /pt          # Portuguese translations
└── /scripts             # Utility scripts for the project

```

## 🏗️ Getting Started

Follow the steps below to set up the project locally.

### ✅ Prerequisites

Ensure you have the following installed:

- **Node.js** (>= 20.0.0)
- **Yarn** (version 1.22.19 or above)

### 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-repo/sbmz-customer-portal.git

   cd sbmz-customer-portal

   yarn install
   ```

🚀 Running the Project
To start the development server:

```bash
yarn dev

Once started, visit http://localhost:3000 to view the application in your browser.
```

🔨 Building for Production
To create an optimized production build:

```bash
yarn build
🎯 Starting the Production Server
After building, you can start the production server with:
```

```bash
yarn start
🧹 Linting and Code Formatting
Run ESLint to analyze code quality:
```

```bash
yarn lint

Automatically fix linting issues:
```

```bash
yarn lint:fix

```

```bash
Format the code using Prettier:

yarn format
```

## 🌐 Internationalization

This portal supports the following languages:

🇲🇿 Portuguese
🇺🇸 English
🇨🇳 Chinese
You can switch between these languages using the language selector located in the top-right corner of the app.

### 🔧 Environment Variables

To configure the environment, create a .env.local file at the root of the project and add the following variables:

```bash
NEXT_PUBLIC_API_URL=<Your API URL>
NEXT_PUBLIC_ANALYTICS_ID=<Your Analytics ID>
```

## 🧑‍💻 Development

#### Folder Structure:

components/: Contains reusable React components.
pages/: Next.js page routes and API routes.
public/: Static assets like images and fonts.
styles/: Global CSS and Tailwind configurations.

#### Custom Scripts:

Dev: Start the development server with yarn dev.
Build: Generate a production build using yarn build.
Start: Start the production server with yarn start.
Lint: Check code quality with yarn lint.
Fix Lint: Automatically fix lint issues with yarn lint:fix.
Format: Run Prettier to format your code with yarn format.

### 💡 Contributing

We welcome contributions to improve the portal! Follow the steps below to contribute:

Fork the repository.

Create a new branch for your feature or bugfix:

```bash
git checkout -b feature/new-feature
Make your changes and commit them:
```

```bash
git commit -m "Add new feature"
Push to your branch:
```

```bash
git push origin feature/new-feature
Open a Pull Request!
```

## 📝 Changelog

`v0.1.0`
Initial release with core banking features.
Multilingual support (🇲🇿 Portuguese, 🇺🇸 English, 🇨🇳 Chinese).
Self-service and bot services enabled.

#### 📄 License

This project is licensed under the Standard Bank Mozambique Terms of Use.

💻 Developed by: Standard Bank Mozambique Digital Channels Team.
