# LeadCaptureGeneric - XYZ Bank Digital Lead Capture & Loan Origination

Modern, high-conversion online lead capture portal for digital loan applications (Gold Loan, Home Loan), integrated with CRM lead processing.

## Features
- **Instant On-Submit Thank You Experience**: Seamless transition to a personalized confirmation screen upon submission with reference tracking ID (`XYZ-2026-XXXXXX`) and status timeline.
- **Standalone Thank You Page**: Included `thankyou.html` supporting URL parameters (`?Name=...`) and session persistence.
- **Enhanced Financial UI**:
  - Crisp vector brand assets (`images/bank-logo.svg`, `images/hero-illustration.svg`, etc.)
  - Interactive visual product cards (Gold Loan, Home Loan)
  - Indian Rupee (₹) currency formatting
  - Customer trust badges & 256-bit SSL encryption indicator
- **Preserved Backend Integration**:
  - Full compatibility with backend lead capture endpoints and parameters
  - Retained hidden campaign, layout, and debug fields
  - Client-side validation (`IsValidForm`, `IsValidEmail`, `UpdateProductName`)

## Project Structure
```text
LeadCaptureGeneric/
├── images/
│   ├── bank-logo.svg
│   ├── gold-loan.svg
│   ├── hero-illustration.svg
│   ├── home-loan.svg
│   ├── security-badge.svg
│   └── thank-you-success.svg
├── index (8).html
├── index.html
├── thankyou.html
└── README.md
```

## How to Run
Simply open `index.html` or `index (8).html` in any modern web browser or serve it via any static web server.
