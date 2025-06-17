# LWC iFrame Exercise

A simple Lightning Web Component (LWC) that embeds an external web application using an iFrame on a Salesforce Lightning Home Page.

## Features

- Embeds a configurable iFrame in a Lightning Experience page
- Exposed to Lightning App Pages, Record Pages, and Home Pages
- Designed for profile-based visibility control (e.g., Sales Profile only)
- Compliant with Salesforce CSP Trusted Sites security settings

## Files

- `iframeExercise.js` — Component logic and URL configuration
- `iframeExercise.html` — Template containing the iFrame
- `iframeExercise.js-meta.xml` — Metadata defining component exposure and page targets

## Setup Instructions

1. **Set Trusted Site in Salesforce:**

   - Go to **Setup → CSP Trusted Sites → New**.
