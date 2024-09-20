# NEXT-APP-BOILERPLATE

Welcome to my all-in-one Next.js project with app router!

## Features

- ⚡ [Next.js](https://nextjs.org) with App Router support
- 🔥 Type checking [TypeScript](https://www.typescriptlang.org)
- 💎 Integrate with [Tailwind CSS](https://tailwindcss.com)
- 🖼️ Navigate animation with [next-view-transitions](https://github.com/shuding/next-view-transitions)
- 🧰 Statem management with [Valtio](https://valtio.pmnd.rs/) and [React Query](https://tanstack.com/query/latest/)
- ✅ Strict Mode for TypeScript and React 18
- 📏 Linter with [ESLint](https://eslint.org) (default NextJS, NextJS Core Web Vitals, Tailwind CSS
- 💖 Code Formatter with [Prettier](https://prettier.io)
- 🦊 Husky for Git Hooks
- 🚫 Lint-staged for running linters on Git staged files
- 🚓 Lint git commit with Commitlint
- 🧪 E2E Testing with [Playwright](https://playwright.dev/)
- 💡 Absolute Imports using `@` prefix
- 🗂 VSCode configuration: Debug, Settings, Tasks and extension for PostCSS, ESLint, Prettier, TypeScript, Jest
- 🤖 SEO metadata with Next generateMetadata
- ⚙️ [Bundler Analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)
- 💯 Maximize lighthouse score

## Use the template with create-next-app
To create a new project based on this template using create-next-app, run the following command:

```bash
npx create-next-app -e https://github.com/chongruei/nextjs-app-boilerplate
```

## Requirements
 - Node.js >=20.0.0 and pnpm

## Getting started

To install the dependencies, run the following command:

```bash
pnpm install
```

## Local Configuration

Before starting the development server, make sure to add the local configuration file `.env.local` with the following content:

```plaintext
# GENERATE_SOURCEMAP=false
NEXT_PUBLIC_VERSION=$npm_package_version
NEXT_PUBLIC_ENV=production
NEXT_PUBLIC_ENV_NAME=local
```

## Start Development Server

To start the development server, use the following command:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the application. You can edit the pages by modifying the corresponding files in the `src/app` directory. The changes will be automatically updated in the browser.

## Start Production Server

To start the production server, follow these steps:

```bash
pnpm build
pnpm start
```

## Run Playwright testings

To install the Playwright, run the following command:

```bash
pnpm exec playwright install
```

and

```bash
pnpm test
```

## Bundle Analyzer

To analyze the bundle size, run the following command:

```plaintext
ANALYZE=true pnpm build
```

## Docker Commands

To build and run the application using Docker, you can use the following commands:

```plaintext
docker-compose -f docker-compose.yml build
docker-compose -f docker-compose.yml up
```

# VSCode Developer Setup

To get started with development in Visual Studio Code, open the workspace file named `nextjs-app-router-boilerplate.code-workspace`.

### I18n with next-intl

For internationalization (i18n), we use the `next-intl` package. It provides comprehensive support for localization in Next.js applications.

We recommend installing the following extensions for a better development experience:

- [Auto Import](https://marketplace.visualstudio.com/items?itemName=steoates.autoimport)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)

