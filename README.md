# WorkFlow Pro QA Automation Framework

## Overview

This repository contains a scalable QA Automation Framework developed as part of a technical assessment for a B2B SaaS platform.

The framework demonstrates:

- UI Automation using Playwright
- API Automation using Pytest
- BrowserStack Integration
- Multi-Tenant Testing
- Cross Browser Testing
- Mobile Testing Strategy
- Page Object Model (POM)
- CI/CD Ready Architecture

---

## Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Programming Language |
| Pytest | Test Framework |
| Playwright | UI Automation |
| Requests | API Testing |
| BrowserStack | Cross Browser Testing |
| GitHub Actions | CI/CD |
| Allure | Test Reporting |

---

## Project Structure

```
qa-automation
│
├── api/
├── config/
├── docs/
├── fixtures/
├── pages/
├── reports/
├── screenshots/
├── testdata/
├── tests/
├── utils/
│
├── README.md
├── requirements.txt
├── pytest.ini
└── .env.example
```

---

## Features

- Page Object Model
- API Client Layer
- Environment Configuration
- Retry Mechanism
- Screenshot on Failure
- Logging
- Multi Tenant Support
- BrowserStack Integration
- Parallel Execution
- CI/CD Ready

---

## Run Tests

Install dependencies

```bash
pip install -r requirements.txt
```

Install Playwright

```bash
playwright install
```

Run all tests

```bash
pytest
```
