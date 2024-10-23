# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh



# 3-Tier Rule Engine with AST – Frontend

## Overview
This project implements a rule engine using an Abstract Syntax Tree (AST) for dynamic rule creation, combination, and evaluation. It provides a web-based frontend that allows users to interact with rules using a visual UI.

## Features
- **Dynamic Rule Creation:** Define rules based on conditions such as age, department, and salary.
- **AST Representation:** Rules are represented as AST nodes for efficient processing.
- **Rule Combination:** Merge multiple rules using logical operators (AND/OR).
- **Rule Evaluation:** Test eligibility rules against sample input data.
- **Bonus Features:** 
  - Modify existing rules by editing nodes dynamically.
  - Add user-defined functions to handle advanced logic.

---

## Project Structure
```
3TierRuleEngine-with-AST-Frontend
├── public/                 # Static files (e.g., index.html, favicon)
├── src/
│   ├── components/         # React components for UI elements
│   │   ├── RuleForm.jsx    # Form for rule creation
│   │   ├── RuleList.jsx    # List of created rules
│   │   └── Evaluator.jsx   # Rule evaluation component
│   ├── services/           # Service calls (API placeholders)
│   │   └── apiService.js   # API communication logic (backend integration)
│   ├── utils/              # Helper functions for AST operations
│   │   └── astUtils.js     # AST node manipulation logic
│   └── App.jsx             # Main React component
├── index.html              # HTML entry point
├── package.json            # Project dependencies and scripts
└── vite.config.js          # Vite configuration
```

---

## Setup Instructions
### Prerequisites
- **Node.js** v16 or above  
- **Vite**  
- **NPM** or **Yarn**

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/soam1/3TierRuleEngine-with-AST-Frontend.git
   cd 3TierRuleEngine-with-AST-Frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```
4. Open the application at [http://localhost:5173](http://localhost:5173).

### Building for Production
```bash
npm run build
```

### Linting
```bash
npm run lint
```

---

## Usage
1. **Create Rules:** Use the form to create rules based on your requirements.
2. **Combine Rules:** Merge rules using logical operators (AND, OR).
3. **Evaluate Rules:** Input sample data and check rule outcomes.

---

## Future Improvements
- Add backend API for rule storage and processing.
- Implement user authentication for secured rule management.
- Store rules and metadata in a database (e.g., MongoDB).

---

## Dependencies
- **React** – UI framework  
- **Vite** – Build tool  
- **TailwindCSS** – Styling  
- **ESLint** – Code quality  

---

## Contributing
Feel free to fork the project, submit issues, or create pull requests for improvements.

---

## License
This project is licensed under the MIT License.