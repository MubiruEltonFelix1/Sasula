# Sasula Project Overview

## 1. Project Summary
Sasula is a static product landing page and simple payment-flow simulator for Mobile Money requests and receipt tracking in Uganda.

## 2. Audience
- Small businesses
- Freelancers and service providers
- Schools and organizations collecting structured payments
- Users who want a plain-language guide to the product flow

## 3. Core User Journey
1. A sender opens the request flow, enters an amount, and writes a reason for payment.
2. Sasula generates a simple code or shareable request.
3. The sender shares the code through WhatsApp, SMS, or copy.
4. The payer opens the receive flow, reviews the simulated payment context, and completes the payment journey.
5. The receive dashboard records the transaction and the user can review history or withdraw the balance.

## 4. Product Features
- Request creation with amount, reason, expiry, and share options
- Receive dashboard with wallet, methods, and history tabs
- Simple payment simulations for requester and payer journeys
- How-it-works walkthrough for first-time users
- Documentation section linked from the page footer

## 5. User Documentation
- Start with the user journey section on the page
- Open the request modal to simulate creating a payment request
- Open the receive modal to simulate viewing and settling payments
- Use the how-it-works demo to see the merchant and payer sides side by side
- Refer to this file as the written overview for the site

## 6. UI Notes
- The page uses one main HTML file with inline CSS and JavaScript
- Decorative emoji labels were removed in favor of text-based labels
- The mobile navigation uses a toggle menu for small screens
- Counter values animate when the page loads and when the section becomes visible

## 7. Content And Simulation Notes
- All payment data on the page is simulated and does not connect to a live payment provider
- The generated codes, receipts, and balances are product demos only
- The user flow is intended to feel realistic while staying safe and simple

## 8. Run And Maintenance Notes
- Open index.html in a browser to view the site
- Keep links inside the page pointing to #journey, #how, #receive, and #docs
- Update the documentation section and this file together when the simulated flow changes
- If new scripts are added, keep them readable so flow bugs are easier to spot
