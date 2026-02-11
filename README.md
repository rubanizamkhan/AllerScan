# AllerScan
People with food allergies struggle to quickly identify unsafe ingredients in packaged foods due to complex labels and hidden allergen names, increasing the risk of accidental exposure.
🚀 Features
✅ Phase 1 – Core Allergy Checker (MVP)

Add and manage allergy profile (stored in localStorage)

Paste ingredient list and analyze

Instant SAFE / DANGER result

Highlight detected allergens

Fully responsive, accessible UI

Client-side only (no backend)

🤖 Phase 2 – AI-Powered Detection

Claude (Anthropic) API integration

Detect hidden allergens (e.g., whey → milk, albumin → egg)

Ingredient-wise safety breakdown

Loading states & error handling

Caching recent analyses

📸 Phase 3 – Barcode Scanning

Scan product barcodes using device camera

Fetch ingredients from OpenFoodFacts API

Scan history with export option

Mobile browser support

Offline history access

🧱 Tech Stack

Frontend: React + TypeScript

Styling: Tailwind CSS

Build Tool: Vite

Deployment: Vercel / Netlify

AI: Claude (Anthropic API)

Barcode: @zxing/browser
🎯 Success Metrics
Phase	Goal
Phase 1	Add 5+ allergies and analyze in under 3 clicks
Phase 2	Detect 90%+ hidden allergens in test cases
Phase 3	Successfully scan 80%+ real product barcodes
🎨 Design Principles

⚡ Speed First – Results in under 2 seconds

📱 Mobile-First – Designed for shopping use

🚨 Clear Alerts – No ambiguity in results

🔍 Transparency – Show why something was flagged

🔮 Future Enhancements

User accounts & cloud sync

Nutrition analysis

Restaurant menu scanning

Share safe products with family

Offline product database

Multi-language support

Voice input for ingredients

🛠 Libraries Used

@anthropic-ai/sdk – AI analysis

@zxing/browser – Barcode scanning

lucide-react – Icons

react-hot-toast – Notifications

🔒 Privacy & Safety

No user accounts

Allergies stored locally

No personal data stored on servers

Option to clear all local data

HTTPS required for camera access

♿ Accessibility

Screen reader-friendly alerts

Keyboard navigation

High contrast support

Large touch targets (44px+)

📦 Deployment

Deployed using:

Vercel or Netlify

HTTPS enabled (required for camera access)

Environment variables configured in hosting dashboard

📜 License

This project is for educational and hackathon purposes.
You may use and modify it freely.
