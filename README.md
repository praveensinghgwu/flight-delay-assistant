# DelayBack — Relay Trip Delay Assistant

DelayBack is a browser-based prototype that helps travelers identify potentially reimbursable flight disruptions and prepare a claim packet. Relay is the conversational assistant inside the experience.

## Open the prototype

No installation is required. Download the repository, then double-click `index.html` to open it in a modern web browser.

## Prototype loop

1. Ask Relay to search the sample inbox for eligible flights.
2. Relay compares the discovered trips with a sample card reimbursement policy.
3. Review eligible and ineligible trips on the flight dashboard.
4. Select an eligible trip and start a claim.
5. Upload the cancellation letter, card statement, and receipts.
6. Review and approve the claim.
7. Download the final claim packet.

## Important limitations

This portable prototype uses built-in sample records. It does not contain private Google, Gemini, email, card, or flight API credentials. Microphone, speech, and camera behavior depends on browser support and permissions. Eligibility results are estimates and do not replace the official decision of a card issuer, insurer, or claims administrator.

## Privacy

The standalone version runs entirely in the browser. Uploaded filenames and prototype state are not sent to a server and are cleared when the page is refreshed.
