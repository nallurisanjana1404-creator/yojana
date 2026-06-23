# 🇮🇳 GovAI – Government Schemes Recommendation Platform

An AI-powered Government Schemes Discovery and Assistance Platform designed to help Indian citizens find eligible government welfare schemes, verify documents, receive personalized recommendations, and interact with a multilingual AI assistant.



## 🚀 Features

### 🤖 AI Scheme Recommendation Engine

* Personalized scheme matching based on:

  * Age
  * Gender
  * Income
  * Education
  * Occupation
  * Social Category
  * Minority Status
  * Disability Status
  * Widow / Single Mother Status
* AI-generated eligibility insights
* Match score (0–100)
* Personalized action tips

### 📄 AI Document Verification

* Aadhaar Card Verification
* Income Certificate Verification
* Caste Certificate Verification
* Readiness Score Generation
* Missing Document Detection
* Smart Fallback Verification System

### 💬 Multilingual AI Chatbot

Supports:

* English
* हिंदी (Hindi)
* తెలుగు (Telugu)

Capabilities:

* Government Scheme Guidance
* Eligibility Queries
* Required Documents Support
* Application Process Guidance
* Scheme FAQs

### 📊 Eligibility Dashboard

* User Profile Management
* Scheme Match Analysis
* Eligibility Tracking
* Progress Monitoring

### 🛣️ Application Roadmaps

Step-by-step guidance for:

* Scholarship Applications
* Farmer Schemes
* Pension Schemes
* Women Welfare Schemes
* Health Insurance Schemes

### 🔐 Secure User Authentication

* Registration
* Login
* Profile Management
* Session Handling

---

## 🛠️ Tech Stack

### Frontend

* React
* TypeScript
* Tailwind CSS v4
* Vite

### Backend

* Node.js
* Express.js
* TypeScript

### AI Integration

* Google Gemini 2.5 Flash API

### Database

* JSON-based Storage
* Extendable to MongoDB / PostgreSQL

---

## 📂 Project Structure

```text
GovAI/
│
├── client/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── App.tsx
│
├── server/
│   ├── routes/
│   ├── services/
│   └── server.ts
│
├── data/
│   ├── schemes.json
│   ├── users.json
│   └── documents.json
│
├── public/
│
├── .env
├── package.json
└── README.md
```

---


Analyzes:

* Income
* Occupation
* Age
* Education
* Social Category

Returns:

```json
{
  "schemeId": "pm-kisan",
  "matchScore": 92,
  "recommendationReason": "Eligible farmer with income criteria satisfied.",
  "actionTip": "Link Aadhaar with land records."
}
```

---

### Document Verification

Returns:

```json
{
  "success": true,
  "readinessScore": 90,
  "notes": "Document verified successfully.",
  "missingDocuments": []
}
```

---

## 🌐 Supported Government Schemes

Examples:

* PM-KISAN
* Ayushman Bharat
* Sukanya Samriddhi Yojana
* Pragati Scholarship
* National Scholarship Portal Schemes
* Old Age Pension Schemes
* Women Welfare Programs

---

## 🔒 Security Features

* Environment Variable Protection
* API Validation
* Error Handling
* Offline Fallback Systems
* Secure User Profile Processing

---

## 🎯 Future Enhancements

* OCR-based Document Reading
* Real-Time Government API Integration
* Voice-to-Voice Assistant
* Mobile App Version
* Aadhaar e-KYC Integration
* GIS-Based Scheme Availability Mapping

-

## 📜 License

This project is developed for educational, research, and social impact purposes.

MIT License.
