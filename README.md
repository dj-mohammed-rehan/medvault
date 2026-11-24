# MedVault

A prototype for organizing and sharing digital health records through QR-linked patient views.

MedVault explores a patient and doctor workflow for organizing records and opening patient views through QR codes. The current implementation is a prototype, not a secure health-record service.

## Live demo

[Open the MedVault fictional-data demo](https://dj-mohammed-rehan.github.io/medvault/).

The live site is a separate, browser-only demo in `docs/index.html`, using fictional people and sample documents. It has no signup, passwords, uploads, backend or AI health chat. It is not a secure health-record service. The original React and Express source remains for development only.

## Prototype status

Prototype only. Do not use real patient information, real medical files or reused passwords. Authentication, access controls and private file storage need work before a public launch.

## Features

- Digital health records that patients carry with them
- QR-based navigation to patient record views
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
