# Next.js Template with TailwindCSS and TypeScript

This is a starter template for building web applications using Next.js with a comprehensive set of tools and libraries to enhance your development workflow and ensure code quality. It includes support for TailwindCSS, TypeScript, ESLint, Prettier, Husky, Lint Staged, Commitlint, Jest, React Testing Library, and Github Actions.

## Features

- **Next.js:** A popular React framework for building server-rendered React applications.
- **TailwindCSS:** A utility-first CSS framework for building responsive and customizable UI components.
- **TypeScript:** A strongly typed superset of JavaScript that enhances code quality and developer productivity.
- **ESLint:** A pluggable linting utility for JavaScript and TypeScript.
- **Prettier:** An opinionated code formatter to ensure consistent code style.
- **Husky:** A tool that enables Git hooks to prevent bad commits and automate tasks.
- **Lint Staged:** A tool that runs linters on pre-committed files.
- **Commitlint:** A tool for linting commit messages to enforce a consistent commit message format.
- **Jest:** A popular JavaScript testing framework for writing and running unit tests.
- **React Testing Library:** A set of utilities for testing React components.
- **Github Actions:** Automated CI/CD workflows to ensure code quality and deploy your app.

## Getting Started

Follow these steps to get started with your project:

1. **Clone the Repository:** Use `git clone` to clone this repository to your local machine.
2. **Install Dependencies:**

   - Using npm: Run `npm install`
   - Using Yarn: Run `yarn`
   - Using pnpm: Run `pnpm install`

3. **Development:** Start the development server with:

   - Using npm: `npm run dev`
   - Using Yarn: `yarn dev`
   - Using pnpm: `pnpm dev`

4. **Linting and Formatting:**

   - Using npm: Run `npm run lint` to lint your code and `npm run format` to format it.
   - Using Yarn: Run `yarn lint` to lint your code and `yarn format` to format it.
   - Using pnpm: Run `pnpm lint` to lint your code and `pnpm format` to format it.

5. **Testing:** Write and run tests using:

   - Using npm: `npm test`
   - Using Yarn: `yarn test`
   - Using pnpm: `pnpm test`

6. **Continuous Integration:** Github Actions workflows are set up for automated testing and deployment. Customize the workflows in the `.github/workflows` directory.
7. **Customization:** Customize the project as per your requirements. Add new components, pages, styles, and more.
8. **Deployment:** Deploy your application to the hosting platform of your choice using the appropriate commands or configurations.

## Folder Structure

```
/
├── .github/
│   └── workflows/        # Github Actions workflows
├── .husky/               # Husky configuration
├── src/
│   └── app/              # Next.js pages
│   └── components/       # React components used in pages
│   └── utils/            # Utility functions
├── .jest/                # Jest setup files
├── .eslintrc.json        # ESLint configuration
├── .gitignore            # Git ignore rules
├── .prettierrc           # Prettier configuration
├── commitlint.config.js  # Commitlint configuration
├── jest.config.mjs       # Jest configuration
├── next.config.js        # Next.js configuration
├── package.json          # Project dependencies and scripts
├── README.md             # Project README (you're here!)
├── postcss.config.js     # PostCSS configuration
├── tailwind.config.js    # TailwindCSS configuration
└── tsconfig.json         # TypeScript configuration

```