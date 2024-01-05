# Configuring a Sui dApp for Movement Network

In this guide for Sui developers, we'll learn how easy it is to create a Sui dApp React frontend and configure your dApp for Movement Network's M2 blockchain.

## Create a new Sui dApp project with `@mysten/create-dapp` 

```
pnpm create @mysten/dapp
```

([Install pnpm](https://pnpm.io/installation) first if needed.)

When you're asked `Which starter template would you like to use?`, select `react-e2e-counter`.

Then give your app a unique name or use the default name, `my-first-sui-dapp`.

Navigate into your dApp's folder:

```
cd <your dapp name>
```
Open the dApp codebase with your favorite editor:
```
code .
```
Install dependencies:
```
npm install
```
And run your dApp locally:
```
npm run dev
```
Your dApp will appear in your browser:

[todo: insert dApp screenshot]

## Configure your Sui dApp for Movement Network (M2)
Movement's M2 blockchain is currently the preferred target for deploying Sui Move modules.

We'll 

