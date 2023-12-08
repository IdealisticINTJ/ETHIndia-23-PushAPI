This is an [EVM Kit](https://evmkit.com/) project bootstrapped with `npx evmkit create`.

## Getting Started

Open the project in [Visual Studio Code](https://code.visualstudio.com/).
The repository comes with a set of [recommended extensions](https://github.com/jarrodwatts/evmkit/blob/main/template/.vscode/extensions.json)
for building web3 apps; when you open the project, VS Code will prompt you to install them.
For the best IDE experience, it's recommended to install these extensions.

## Installation

The application is split into two directories, `application`, and `contracts`; for the frontend and smart contracts respectively.

The recommended way to use the IDE for this setup is to open a new [split terminal](https://code.visualstudio.com/docs/terminal/basics#:~:text=Multiple%20terminals%20can%20be%20placed,tab%20on%20the%20terminal%20panel.)
inside your VS Code window; one for each directory.
This way, you can work simultaneously on the frontend and smart contracts.

First, install the dependencies for each directory. See the sections below for more information:

1. [application](#application) - setup the frontend application
2. [contracts](#contracts) - setup the smart contracts

### application

```bash
# 1. Change directory to the application folder
cd application

# 2. Install dependencies
yarn

# 3. Start the application
yarn dev
```

### contracts

```bash
# 1. Change directory to the contracts folder
cd contracts

# 2. Install dependencies
yarn

# 3. Build the contracts (optional)
yarn build
```

You'll now be able to view your application at [http://localhost:3000](http://localhost:3000).

## Learn More

# To learn more about EVM Kit, take a look at the [documentation](https://docs.evmkit.com/).

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
