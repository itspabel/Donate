# Donate

A lightweight donation landing page for supporting the tools and projects maintained by Tasfiqul Alam Pabel.

This repository contains a single-page static website that lets visitors:

- choose a mobile wallet to donate via bKash, Nagad, Upay, or Pathao Pay
- scan a Bangla QR code for payment
- send crypto on Avalanche C-Chain to a wallet address
- copy payment details with one click
- contact the maintainer via WhatsApp

## Live demo

The site is published on GitHub Pages:

https://itspabel.github.io/Donate/

## Project structure

- `index.html` — the complete static landing page and donation UI
- `LICENSE` — project license
- `README.md` — project documentation

## Features

- responsive donation page for desktop and mobile
- copy-to-clipboard buttons for wallet numbers and crypto address
- donation options with branded cards for each payment method
- QR code section for Bangla QR payments
- crypto token selector for USDT, USDC, and AVAX
- safe and simple static HTML/CSS/JavaScript implementation

## How to use

1. Clone the repository:

   ```bash
   git clone https://github.com/itspabel/Donate.git
   cd Donate
   ```

2. Open `index.html` in a browser, or serve the site locally:

   ```bash
   python -m http.server 8000
   ```

3. Visit `http://localhost:8000` in your browser.

## Customization

The donation details are configured in the `CONFIG` object near the end of `index.html`:

- wallet names and numbers
- Pathao Pay URL
- QR image path
- crypto address
- token list

You can update those values to match your own donation information.

## License

This project is licensed under the Creative Commons Zero v1.0 Universal license.

See the [LICENSE](LICENSE) file for more details.

## Notes

The page currently includes a warning that crypto funds should only be sent on the Avalanche C-Chain network, as tokens sent on the wrong chain may not be recoverable.
