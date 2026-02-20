# DataNimbus Systems - Policy Demo Page

This project provides a production-grade, fictional Privacy Policy and Terms of Service page designed for testing deterministic legal diff engines.

## Purpose

The `PolicyDemoPage` component is specifically crafted to validate the following capabilities of a legal diff engine:
- **Section Extraction:** Consistent `h1`, `h2`, and `h3` hierarchy for parsing.
- **Structural Diffing:** Realistic nesting of clauses and sub-clauses.
- **SHA-256 Hashing:** Stable content structure for section-level hashing.
- **Fuzzy Matching:** Realistic section titles for testing title-matching algorithms.
- **Risk Detection:** Naturally embedded high-risk legal keywords (e.g., "class action waiver", "arbitration", "biometric data").
- **Performance:** Large content volume (~5,000 words) to test handling of complex documents.

## Key Features

- **Fictional Company:** DataNimbus Systems (Cloud Analytics SaaS).
- **Structured Content:** Pure HTML elements (`h1`, `h2`, `h3`, `p`, `ul`, `li`, `table`).
- **Comprehensive Coverage:**
  - Privacy Policy (Intro, Definitions, Collection, Use, Sharing, Retention, etc.)
  - Terms of Service (Acceptance, Billing, Automatic Renewal, Refund Policy, etc.)
  - Acceptable Use Policy
- **Embedded Risk Keywords:** Realistic contractual language containing high-risk and medium-risk legal terms.

## Project Structure

- `src/PolicyDemoPage.tsx`: The main React component containing the legal text.
- `src/App.tsx`: Renders the demo page for immediate viewing.

## Getting Started

### Prerequisites

- Node.js (v18+)
- npm

### Installation

```bash
npm install
```

### Development

Start the development server:

```bash
npm run dev
```

### Build

Compile the project for production:

```bash
npm run build
```

## Content Requirements Reference

- **Minimum Word Count:** ~5,000+ words.
- **Styling:** Minimal inline styling for readability; uses standard HTML semantic tags.
- **Legal Compliance:** Fictional content only. Do not use for real legal purposes.
