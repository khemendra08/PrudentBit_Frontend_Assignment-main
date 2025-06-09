# PrudentBit_Frontend_Assignment
# 🏥 Patient Directory - Next.js Assignment

This is a frontend web application built with *Next.js, **TypeScript, and **TailwindCSS, implementing both a **table view* and a *card view* UI for displaying patient data fetched from a REST API.

---

## 📦 Tech Stack

•⁠  ⁠*Next.js (App Router)*
•⁠  ⁠*TypeScript*
•⁠  ⁠*TailwindCSS*
•⁠  ⁠*shadcn/ui* (optional UI primitives)

---

## 🎯 Features

•⁠  ⁠[x] API integration for fetching patient records
•⁠  ⁠[x] Table View with sorting, searching, and pagination (manual or infinite scroll optional)
•⁠  ⁠[x] Card View with responsive layout
•⁠  ⁠[x] Debounced search for performance
•⁠  ⁠[x] Conditional rendering and empty state handling
•⁠  ⁠[x] Strict TypeScript types and modular code structure

---

## 🚀 Getting Started

### 1. Clone the repository
```bash

cd patient-directory
2.⁠ ⁠Install dependencies
bash
Copy
Edit
npm install
3.⁠ ⁠Run the development server
bash
Copy
Edit
npm run dev
Then open http://localhost:3000 in your browser.

🔧 Project Structure
pgsql
Copy
Edit
.
├── app/
│   ├── page.tsx            # Main entry (default to Table or Card View)
│   ├── card-view/page.tsx  # CardView page
│   └── table-view/page.tsx # TableView page
├── components/
│   ├── PatientCard.tsx     # Card View component
│   └── PatientTable.tsx    # Table View component
├── lib/
│   └── api.ts              # API functions
├── styles/
│   └── globals.css         # TailwindCSS entry
├── tailwind.config.js
├── postcss.config.js
└── README.md
