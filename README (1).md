# Openverse — Web3 Landing Page

Openverse is a responsive, beginner-friendly landing page that introduces the basics of Web3 through short explanations and interactive elements.

## Features

- Six clickable concept cards covering blockchain, decentralization, cryptocurrency, smart contracts, NFTs, and DAOs
- Examples for each concept in a pop-up dialog
- Three-question interactive quiz with instant feedback and a restart option
- Responsive layout and mobile navigation
- Optional browser-wallet connection
- Keyboard-accessible controls and reduced-motion support

## Getting started

1. Save `openverse-working.html` on your computer.
2. Open it in a modern web browser. No build tools or dependencies are needed for the learning content and quiz.
3. Click a concept card to see an example, or scroll to the quiz to test what you learned.

If you want to test wallet connection, open the page in a browser with a compatible injected wallet (such as MetaMask). If connecting from a downloaded file does not work in your browser, serve the file locally instead:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000/openverse-working.html` in that browser.

## Wallet behavior and safety

The **Connect wallet** button requests access to a public wallet account through `window.ethereum` when a compatible wallet is present. If no wallet is detected, it shows a helpful message. Connecting is optional; the site does not request a signature, initiate a transaction, ask for a recovery phrase, or require cryptocurrency. Always review wallet prompts before approving them.

## Built with

HTML, CSS, and vanilla JavaScript in a single file. No external packages, API keys, or backend are required.

## Files

- `openverse-working.html` — complete landing page and interactive functionality
- `README.md` — setup and feature overview
