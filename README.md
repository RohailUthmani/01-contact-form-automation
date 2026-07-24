# Contact Form Automation

## Overview

This project is a Make.com automation workflow that processes Google Form submissions automatically.

When a user submits the contact form, the workflow:

1. Receives the form response
2. Sends an automatic email reply using Gmail
3. Stores the submission data in Google Sheets


## Workflow Architecture

Google Forms
→ Gmail
→ Google Sheets


## Tools Used

- Make.com
- Google Forms
- Gmail
- Google Sheets


## Automation Flow

1. Google Forms Watch Responses triggers the scenario.
2. Form data is mapped into the Gmail module.
3. Gmail sends an automated response.
4. Google Sheets stores the submission details.


## What I Learned

- Understanding Make.com scenarios
- Working with trigger modules
- Connecting applications using modules
- Data mapping between modules
- Testing automation workflows


## Files

- `contact-form-automation-blueprint.json` - Make.com scenario export
- `scenario-success.png` - Working automation screenshot
