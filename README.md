# Wallet Age Checker

A **single-page** web app that shows **when a Bitcoin or Ethereum wallet was first funded** (its age).

![Demo screenshot](https://raw.githubusercontent.com/YOUR_USERNAME/wallet-age-checker/main/screenshot.png)

## Features
- No backend, no database – pure client-side.
- Works with **Bitcoin** (Blockstream) and **Ethereum** (Etherscan).
- Shows exact date + human-readable age (days/hours/min).

## Live Demo
[https://YOUR_USERNAME.github.io/wallet-age-checker/](https://YOUR_USERNAME.github.io/wallet-age-checker/)

## How to use
1. Open `index.html` in any browser.
2. Paste a **public address**.
3. Select chain → **Check**.

> **Ethereum**: Replace `YOUR_ETHERSCAN_API_KEY` in `index.html` with a free key from [etherscan.io/myapikey](https://etherscan.io/myapikey).

## Local development
```bash
git clone https://github.com/YOUR_USERNAME/wallet-age-checker.git
cd wallet-age-checker
# Just open index.html
