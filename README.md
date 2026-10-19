# JomiGuard AI 🌿

**AI-Powered Land Document Digitization & Comparison for Bangladesh**

JomiGuard AI is a land-tech platform designed to help users digitize sample land records, extract important information, compare documents, and identify missing or inconsistent fields that require further verification.

Developed as a prototype for the LandTech Innovation Hackathon 2026.

## 🎯 Problem

Land documents such as deeds and khatians can be difficult to read, search, and compare, particularly when they are scanned or contain Bangla text. Manually identifying differences across multiple documents can be time-consuming.

## 💡 Our Solution

JomiGuard AI combines document processing, structured data extraction, and comparison tools to support preliminary land-document screening.

### Key Features

- 📄 Document upload and preview
- 🔎 OCR and AI-assisted data extraction
- 🗂️ Structured land-record management
- ⚖️ Field-by-field document comparison
- 🚩 Detection of missing and inconsistent information
- 📊 Clear comparison summaries
- 📝 Preliminary report generation
- 🇧🇩 Bangla-friendly user experience

## 🛠️ Technology Stack

- Frontend: React and TypeScript
- Build tool: Vite
- AI: Google Gemini API, if configured
- Data layer: Depends on the implemented project configuration

See the source code and setup instructions for the technologies actually implemented.

## 🚀 Getting Started

### Prerequisites

- Node.js and npm
- Git
- A Gemini API key if AI-powered features require one

### Installation

```bash
git clone https://github.com/YOUR-GITHUB-USERNAME/jomiguard-ai.git
cd jomiguard-ai
npm install
```

### Environment Setup

Create a `.env` file using the project's `.env.example` as a guide.

Configure required environment variables according to the implemented application. Keep API keys private and never commit secrets to GitHub.

### Run Locally

```bash
npm run dev
```

Follow the terminal output to open the application in your browser.

## 🧪 Demo Data

The prototype uses fictional sample records to demonstrate document extraction and comparison.

Demo data does not represent real land records or verified ownership information.

## 🔐 Privacy and Responsible Use

- Use synthetic or explicitly authorized sample documents.
- Do not upload sensitive personal or real land records to an unapproved service.
- Keep API credentials private.
- Review extracted values against their source documents.
- Treat comparison results as preliminary screening only.

## ⚠️ Limitations

JomiGuard AI does not officially verify land ownership, certify document authenticity, determine legal title, or establish fraud.

A mismatch may result from OCR errors, different document dates, missing information, or other circumstances. Original records should be checked by the appropriate authority or a qualified professional.

Government database integration is not claimed unless explicitly implemented and authorized.

## 🧠 AI Tools and Development

AI-assisted development and document analysis tools may be used during development. The final submission should accurately disclose the tools used and how they contributed to the project.

## 👥 Team

- Snikdho
- Rahimin

Mentor details: To be added if applicable.

## 📄 License

Add an appropriate open-source license if the team intends to publish and permit reuse of the code.

---

**JomiGuard AI — Making land documents easier to understand, compare, and review.**
