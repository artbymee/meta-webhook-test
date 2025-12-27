\# Meta Webhook Test App



This is a simple Node.js + Express application designed to test \*\*Meta (Facebook/WhatsApp) Webhook verification\*\*.  

It responds to Meta’s `hub.challenge` during verification and logs incoming webhook events to the console.



---



\## 🚀 Features

\- Handles \*\*GET\*\* requests for webhook verification.

\- Handles \*\*POST\*\* requests for incoming events (WhatsApp messages, delivery receipts, etc.).

\- Logs all events with timestamps to the Render console.

\- Configurable `VERIFY\_TOKEN` via environment variable.



---



\## 📂 Project Structure



