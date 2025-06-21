# REAL-TIME-COLLABORATIVE-DOCUMENT-EDITOR

COMPANY: CODETECH IT SOLUTIONS

NAME: BUKKAMBUDI MANOJ KUMAR

INTERN ID: CT04DM1172

DOMAIN: FULL STACK WEB DEVELOPMENT

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION:

## Overview
The Real-Time Collaborative Document Editor is a web application enabling multiple users to edit a shared document simultaneously. Built with React, WebSocket, and CSS, it uses the Create React App template for structure. Files include `App.js` (main component), `App.css` (styling), `index.css` (global styles), `App.test.js` (tests), `reportWebVitals.js` (performance), `setupTests.js` (test setup), and `index.js` (entry point).

## Tools and Implementation
- **React**: Manages UI with `useState` and `useEffect` for state and WebSocket handling.
- **WebSocket**: Connects to `ws://localhost:5000` for real-time updates, parsing `init` and `update` messages.
- **CSS**: Styles with flexbox, shadows, and responsive layouts.
- **Jest/React Testing Library**: Supports unit testing (current test is placeholder).
- **Web Vitals**: Tracks performance metrics.
- **Create React App**: Provides project scaffolding.

## Functionality
- Initializes WebSocket on mount, updates textarea on server messages.
- Sends user edits to server, syncing across clients.
- Renders a centered textarea with a heading, styled for usability.

## Strengths
- Real-time sync via WebSocket.
- React’s efficient state management.
- Included testing and performance tools.

## Limitations
- Requires backend implementation.
- Lacks conflict resolution.
- No security or advanced UI features.

## Conclusion
The editor meets real-time collaboration goals with a solid React frontend, needing backend and feature enhancements for full functionality.

OUTPUT:

![Image](https://github.com/user-attachments/assets/daf5d4e6-dc7f-48c9-8ef1-4d97e8d96892)
