# Make.com automations

Blueprints for automations I've built on Make.com. You can read them to see how they're put together, or import them and run them yourself.

## What's here

| Folder | What it does | Built with | Status |
|---|---|---|---|
| [booking-confirmations](booking-confirmations/) | Emails a confirmation for each new booking in a Google Sheet and never sends the same one twice | Google Sheets, Gmail | Running in production |
| [ai-blog-pipeline](ai-blog-pipeline/) | Picks a topic, writes and edits a post, makes the image, publishes to WordPress | OpenAI, Gemini, WordPress, Google Docs | Built for my own blog |
| [lead-audit-builder](lead-audit-builder/) | Finds local businesses, pulls their website traffic, fills in a marketing audit deck for each one | Apify, OpenAI, Google Slides | Working prototype |

## How to use a blueprint

1. In Make, create a new scenario.
2. Click the three dots at the bottom of the editor and choose Import blueprint.
3. Pick the blueprint file from the folder you want.
4. Open each module and connect your own account. Anything in capitals, like `YOUR_SPREADSHEET_ID`, needs your own value.

## What I took out

These are real scenarios, cleaned up for sharing. Account connections, file IDs and test data are gone. In the booking flow, the company name, email copy, phone number and sheet names are placeholders.
