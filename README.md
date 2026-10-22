# Farm Management Application

A web-based farm management application designed to centralize livestock management, milk production tracking, and farm accounting.

The application aims to simplify daily farm operations and maintain organized records for cows, goats, milk production, financial transactions, and related activities.

## 📌 Core Modules

### 🐄 1. Cow Management
- Register and manage cow details.
- Maintain unique identification numbers.
- Record breed, age, gender, and date of birth.
- Track health records and vaccinations.
- Maintain breeding and calving history.
- Track animal status and ownership history.

### 🐐 2. Goat Management
- Register and manage goat details.
- Maintain unique identification numbers.
- Record breed, age, gender, and date of birth.
- Track health, vaccinations, and treatments.
- Maintain breeding and kidding history.
- Track livestock purchases and sales.

### 🥛 3. Milk Production Management
- Record daily milk production.
- Maintain separate records for cows and goats.
- Track morning and evening milk yields.
- Calculate daily and monthly production totals.
- Record milk sales and distribution.
- Track milk prices and revenue.
- Generate production reports.

### 💰 4. Accounts Management
- Record daily income and expenses.
- Track milk sales revenue.
- Record livestock purchases and sales.
- Maintain feed, medicine, veterinary, and equipment expenses.
- Track customer payments and outstanding balances.
- Maintain supplier payments.
- Generate financial summaries and profit-and-loss reports.

### 👥 5. Customer and Supplier Management
- Maintain customer and supplier information.
- Track milk deliveries and sales history.
- Record customer payments and outstanding balances.
- Maintain supplier purchase history.
- Track supplier payments.

### 🌾 6. Feed Management
- Maintain feed inventory and stock levels.
- Record feed purchases and consumption.
- Track feed expenses.
- Monitor stock availability.

### 🩺 7. Animal Health Management
- Maintain veterinary and treatment records.
- Track vaccinations and deworming schedules.
- Record illnesses and medical expenses.
- Schedule upcoming health checks.

### 📊 8. Dashboard and Reports
- Display total cows and goats.
- Show daily milk production.
- Summarize income and expenses.
- Display milk sales and revenue.
- Track outstanding payments.
- Generate date-wise and monthly reports.

### 🔐 9. Authentication and Authorization
- Secure application access.
- Integrate with the backend authentication system.
- Support role-based access where required.
- Protect sensitive financial and livestock information.

*Note: The modules above describe the intended scope of the application. Features will be documented as they are implemented.*

## 🛠️ Technology Stack

### Frontend

| Technology | Purpose |
|---|---|
| React | Component-based user interface |
| TypeScript | Static typing and maintainable application code |
| Vite | Development server and build tooling |
| ESLint | Code quality and linting |
| SCSS | Structured and maintainable stylesheets |
| Bootstrap | Responsive layouts and UI components |

### Backend Integration

The frontend will communicate with the backend through APIs.

Backend implementation and authentication details will be documented according to the actual application architecture.

## 📁 Project Structure

```text
form-frontend/
├── public/                 # Static assets
├── src/
│   ├── assets/             # Images, icons, and other assets
│   ├── components/         # Reusable UI components
│   ├── pages/              # Application pages
│   ├── services/           # API integration
│   ├── styles/             # Global SCSS styles
│   ├── types/              # TypeScript types and interfaces
│   ├── App.tsx             # Main application component
│   ├── App.scss            # Application styles
│   ├── index.scss          # Global styles
│   └── main.tsx            # Application entry point
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── tsconfig.json
└── vite.config.ts
```

*Note: This is a suggested structure. The actual files and directories may differ as development progresses.*

## 🚀 Getting Started

### Prerequisites

- Node.js
- npm
- Git

### 1. Clone the repository

```bash
git clone https://github.com/linkelumalai/form-frontend.git
```

### 2. Navigate to the project directory

```bash
cd form-frontend
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start the development server

```bash
npm run dev
```

Open the local URL displayed in the terminal.

## 📜 Available Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Build the application for production |
| `npm run lint` | Check code quality using ESLint |
| `npm run preview` | Preview the production build |

## 🧹 Code Quality

Run ESLint before committing changes:

```bash
npm run lint
```

Build the application to verify that it compiles successfully:

```bash
npm run build
```

## 🔄 Development Workflow

1. Create a feature branch for new functionality.
2. Implement the feature using React and TypeScript.
3. Use reusable components wherever practical.
4. Maintain consistent styling with SCSS and Bootstrap.
5. Run ESLint and verify the production build.
6. Commit changes with descriptive messages.
7. Push changes to the Git repository.

## 🔮 Potential Future Enhancements

- PDF and Excel report exports.
- Multiple farm or location support.
- Livestock image attachments.
- Advanced milk production analytics.
- Automated vaccination and payment reminders.
- Audit logs for important changes.
- Mobile-friendly farm management workflows.
- Backup and data recovery capabilities.

## 📃 License

A license has not yet been specified.
