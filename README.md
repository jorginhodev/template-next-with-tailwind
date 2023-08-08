<h1 align="center">
  <p align="center">Next.js Template with TailwindCSS and TypeScript</p>
  <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://assets.vercel.com/image/upload/v1662130559/nextjs/Icon_dark_background.png">
      <img src="https://assets.vercel.com/image/upload/v1662130559/nextjs/Icon_light_background.png" height="128">
    </picture>
</h1>

![Dependabot](https://img.shields.io/badge/dependabot-025E8C?style=for-the-badge&logo=dependabot&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)


![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Testing-Library](https://img.shields.io/badge/-TestingLibrary-%23E33332?style=for-the-badge&logo=testing-library&logoColor=white)


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