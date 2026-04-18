# iqbalzulsafari.github.io

Personal portfolio website for **Iqbal Zulsafari** — Data Scientist and Problem Solver. Live at [iqbalzulsafari.com](https://iqbalzulsafari.com).

## Overview

A single-page portfolio built with vanilla HTML, CSS, and JavaScript. No frameworks or build tools — just a self-contained `index.html` with embedded styles and scripts. Hosted on GitHub Pages with a custom domain.

## Structure

```
.
├── index.html          # Main portfolio page (all content, styles, and scripts)
├── CNAME               # Custom domain: iqbalzulsafari.com
├── .gitignore
└── assets/
    ├── photo.jpg                       # Profile photo
    ├── Iqbal_CV.pdf                    # Full curriculum vitae
    ├── Iqbal_Resume_Consulting.pdf     # Consulting-focused resume
    ├── Iqbal_Resume_Technical.pdf      # Technical-focused resume
    └── badges/                         # Certification badge images
```

## Sections

| Section | ID | Description |
|---|---|---|
| Hero | `#hero` | Intro, stats, and call-to-action buttons |
| About | `#about` | Core strengths and working style |
| Education | `#education` | UM BSc (AI), Foundation, SPM |
| Work | `#work` | Consulting case studies (3 engagements) |
| Certifications | `#certifications` | 8 credentials from Google, Microsoft, PMI, IBM, NVIDIA, and others |
| Resume | `#resume` | Download links for CV and resumes |
| Contact | `#contact` | Email and LinkedIn |

## Featured Work

**01 — Automating loan application review with AI** *(Banking, Kyndryl 2025)*
Azure Document Intelligence pipeline that classifies documents, extracts data via OCR/NLP, and cross-validates customer details from email-submitted loan applications.
`Azure Document Intelligence · Logic Apps · Azure Functions · Python · OCR/NLP`

**02 — Automating clinical genomics reporting with AI** *(Healthcare, Kyndryl 2025)*
GCP-based report verification module for clinical variant interpretation. Achieved ~90% cost reduction vs. traditional interpreter tool subscriptions.
`Python · GCP Cloud Run · BigQuery · Vertex AI · Cloud SQL · Cloud Bigtable`

**03 — Turning customer chatter into structured business intelligence** *(PropTech, UM × SkyWorld 2024–25)*
Multilingual chatbot and sentiment analytics system for SkyWorld Development Berhad. Supports Malay, Chinese, and English using mBERT and SeaLLM.
`Python · FastAPI · mBERT · SeaLLM · Hugging Face · Streamlit · MySQL`

## Certifications

- Google Associate Data Practitioner (Mar 2026)
- Microsoft Azure Fundamentals — AZ-900 (Jul 2025)
- Microsoft Azure AI Fundamentals — AI-900 (Jul 2025)
- PMI Predictive Project Management (Jun 2025)
- IBM Data Science Foundations Level 1 (2024)
- NVIDIA AI for Anomaly Detection (Dec 2024)
- University of Helsinki — Ethics of AI, 2 ECTS (Dec 2024)
- Cisco CCNAv7: Introduction to Networks (Jun 2022)

## Tech

**Languages:** Python, SQL, JavaScript  
**Cloud:** Microsoft Azure, Google Cloud Platform  
**ML/AI:** Hugging Face, Vertex AI, mBERT, SeaLLM, Azure Document Intelligence  
**Backend:** FastAPI, Azure Functions, GCP Cloud Run  
**Data:** BigQuery, Cloud SQL, Cloud Bigtable, MySQL  
**Other:** Azure Logic Apps, Streamlit, OCR/NLP

## Design

- Font: [DM Sans](https://fonts.google.com/specimen/DM+Sans) + [DM Serif Display](https://fonts.google.com/specimen/DM+Serif+Display)
- Light and dark mode with CSS custom properties
- Scroll-triggered reveal animations
- Fully responsive layout

## Deployment

Hosted on **GitHub Pages**. Push to `main` and GitHub deploys automatically. Custom domain configured via `CNAME` and DNS settings at the registrar.
