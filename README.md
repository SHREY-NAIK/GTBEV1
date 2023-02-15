# Gimbal Bounty Experiment

## How to use:

### 1. Grab this repo
```
git clone https://github.com/SHREY-NAIK/GTBEV1.git
cd gimbal-tracker
npm install
npm run start
```
Your site is now running at http://localhost:8000!

### 2. Configure your project instance
- See `project-variables-testnet-v2.md`

### 2. Use with Cardano `testnet` or `mainnet`
#### in `/src/components/WalletButton/WalletButton.jsx`, look for
```
if ((await window.cardano.getNetworkId()) === 0) return true;
```
- Testnet -> `0` | Mainnet -> `1`


## This project is built with
1. [Gatsby JS](https://www.gatsbyjs.com/docs/?utm_source=starter&utm_medium=readme&utm_campaign=minimal-starter)
2. Chakra UI
3. Easy Peasy for local state management

See `package.json` for full details.

![gimbal](https://user-images.githubusercontent.com/47191058/219077070-4350b5c2-2348-4f4a-a6d5-383d4d757bfd.png)
