# TON Connect demo app

It is an example of an app that connects to TON wallet via TON Connect using [@tonconnect/sdk](https://www.npmjs.com/package/@tonconnect/sdk).

[Try the demo here](https://ton-connect.github.io/demo-dapp/)

## TON Connect UI 

Beta version of the UI kit [@tonconnect/ui-react](https://www.npmjs.com/package/@tonconnect/ui-react).

[Try the UI demo here](https://ton-connect.github.io/demo-dapp-with-react-ui/) (WIP)

## Getting started

1. Install dependencies `yarn`
2. Start development server `yarn start`

## Deploying to Vercel

Step-by-Step Manual Deployment Process

Framework Preset: `Other`

Build Command: `DISABLE_ESLINT_PLUGIN=true BUILD_PATH='./docs' node scripts/build.js`

Output Directory: `docs`

Install Command: `yarn install`

Add Environment Variables:

Go to Project Settings → Environment Variables

Add: `DISABLE_ESLINT_PLUGIN` = `true`

Add: `PUBLIC_URL` = `/`

Deploy and Test:

Click Deploy

Check the build logs for any errors

Test your deployed app functionality
