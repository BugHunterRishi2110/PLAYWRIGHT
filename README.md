# Playwright Automation Framework (TypeScript)

This repository contains an end-to-end (E2E) test automation framework built using **Playwright** and **TypeScript**.  
It supports cross-browser execution, parallel runs, detailed HTML reporting, and scalable test structure using best practices.

---

## ✅ Tech Stack
- Playwright
- TypeScript
- Node.js / npm

---

## ✅ Features
- Cross-browser testing (Chromium, Firefox, WebKit)
- Headless and headed execution
- Parallel execution
- Auto retries (config based)
- Screenshots & video recording on failure (config based)
- Playwright HTML Report generation

---

## ✅ Project Structure
```bash
.
├── tests/                  # All test cases (.spec.ts)
├── pages/                  # Page Object Model classes
├── utils/                  # Helper functions / reusable utilities
├── fixtures/               # Test data / sample JSON files
├── playwright.config.ts    # Playwright configuration
├── package.json            # Project dependencies and scripts
└── README.md               # Documentation