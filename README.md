# Supply Chain Control Tower

An end-to-end intelligent supply chain management platform featuring automated procurement, multi-city logistics tracking, smart dock scheduling, and 3-way invoice reconciliation.

---

## 🚀 Key Features

- **AI-Powered Procurement**: NLP-driven requisition parsing and automated multi-criteria supplier evaluation scoring.
- **Logistics & Fleet Tracking**: Real-time truck tracking with dynamic ETA estimation and route risk analysis.
- **Yard & Dock Operations**: Automated dock allocation algorithms optimizing turnaround times.
- **Finance & 3-Way Matching**: Automated reconciliation of Purchase Orders, Goods Receipts, and Invoices.

---

## 🛠 Tech Stack

- **Frontend**: Next.js 15 (App Router), React, TypeScript, Tailwind CSS, Radix UI
- **Backend**: FastAPI (Python), SQLAlchemy, Pydantic, Gemini API
- **Data & Analytics**: Custom Logistics Dataset, Pandas, NumPy

---

## ⚙️ Quick Start

### 1. Backend Setup
\`\`\`bash
cd backend
python -m venv venv
# On Windows: venv\Scripts\activate | On macOS/Linux: source venv/bin/activate
pip install -r requirements.txt
cp .env.example .env
uvicorn app.main:app --reload --port 8000
\`\`\`

### 2. Frontend Setup
\`\`\`bash
cd frontend
npm install
npm run dev
\`\`\`
Visit `http://localhost:3000` to interact with the application.
