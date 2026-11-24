# MedVault

A portable digital health record system for patients and doctors, with secure sharing via QR codes.

MedVault keeps a person's health records in one place and makes them easy to share. A patient can carry their history on their phone, and a doctor can view the relevant records by scanning a secure QR code instead of handling paper files.

## Features

- Digital health records that patients carry with them
- Secure record sharing with doctors through QR codes
- Camera-based QR scanning
- Works in the browser, no installation needed

## Tech stack

- React 19, TypeScript and Vite
- Tailwind CSS 4
- Express backend
- Google Gemini API (`@google/genai`)
- `react-qr-code` and `html5-qrcode` for QR generation and scanning

## Run locally

**Prerequisites:** Node.js

1. Install dependencies:
   ```bash
   npm install
   ```
2. Set `GEMINI_API_KEY` in `.env.local` to your Gemini API key
3. Start the dev server:
   ```bash
   npm run dev
   ```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
