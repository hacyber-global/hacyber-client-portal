# HacyberGlobalTech | Client Control & Payment System.

Official secure intake, client control, and payment gateway portal for
**Hacyber Global Tech**, engineered to process client project onboarding and route secure payments directly into administrative channels.

## ✨ Features & Architecture

* **Secure Payment Routing**: Streamlined options for direct checkout via Zelle, PayPal, and Bitcoin (BTC) with instant one-click copy-to-clipboard functionality.
* **Integrated Lead Intake Form**: Collects client details and payment transaction hashes, feeding data directly into administrative backend workflows.
* **Direct Telegram Webhook Dispatch**: Automatically routes submitted lead details and payment references directly to your secure management channel via Google Apps Script.
* **Optimized Cyberpunk Interface**: Built with a sleek, responsive, dark-themed UI tailored for optimal user experience across all devices.

## 🛠️ Tech Stack

* **Frontend**: Responsive Single-File HTML5 / CSS3 / Vanilla JavaScript.
* **Backend Integration**: Google Apps Script Webhook API.
* **Deployment & Hosting**: Global edge deployment via Vercel / GitHub Pages.

## 🚀 Deployment Guide

1. Clone or download the repository into your local workspace.
2. Ensure your backend Google Apps Script webhook URL is correctly bound in the fetch request endpoint.
3. Deploy to production using Vercel CLI:
   ```bash
   vercel --prod
