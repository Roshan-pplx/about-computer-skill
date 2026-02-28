# Browser Automation

Computer can control a real cloud browser to interact with websites that require login, JavaScript rendering, or complex interactions.

## What it can do

- Log into websites using saved credentials or user-provided ones
- Fill out and submit forms
- Click buttons, navigate pages, and interact with dynamic UI elements
- Extract content from JavaScript-rendered pages (SPAs, dashboards)
- Take screenshots of web pages
- Automate multi-step web workflows (e.g., book a flight, submit an application)
- Handle pagination and batch-extract data across many pages

## How to trigger it

Users can ask Computer to:
- "Go to [website] and [do something]"
- "Log into my [service] and [extract/submit/check something]"
- "Fill out this form at [URL]"
- "Take a screenshot of [URL]"

## Limitations

- Requires user to provide credentials for login-gated sites (Computer doesn't store passwords by default)
- May struggle with CAPTCHA or bot-detection systems
- Not suitable for high-frequency automation (rate limits apply)
- Cannot interact with browser extensions or local browser profiles
