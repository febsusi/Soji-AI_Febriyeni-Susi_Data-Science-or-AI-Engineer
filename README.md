# Soji-AI_Febriyeni-Susi_Data-Science-or-AI-Engineer
Executive Summary: This report details the methodology used to extract applicability rules from AD PDFs, structures the extracted rules in a machine-readable format, and evaluates whether specific aircraft configurations are affected. In this report, Airworthiness Directives (AD) parser system testing has been completed by evaluating 10 aircraft units against two ADs, namely FAA-2025-23-53 and EASA-2025-0254.

The system uses:
- Beautiful Soup for HTML parsing
- pdfplumber for PDF extraction
- This is a deterministic rule-based system, not an LLM-based classifier.

## Project Structure
├── AI_Engineer_Febriyeni Susi_Soji.ipynb
├── report.md
└── README.md

## Install Dependencies
Run this in a notebook cell:

!pip install requests pdfplumber pandas beautifulsoup4 pydantic

## How to Run
Run all cells sequentially (Kernel → Restart & Run All recommended).
