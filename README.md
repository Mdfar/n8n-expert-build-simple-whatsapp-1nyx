Dental Practice n8n Automation Engine
Modules Included:

Missed Call Recovery: Instantly triggers a WhatsApp message when a webhook is received from your VoIP provider (Twilio, Zadarma, etc.).

AI Booking: Uses OpenAI GPT-4o to chat with patients and manage Google Calendar slots.

Review Generator: Polls finished appointments and sends a feedback request link.

24h Reminders: Automated notification flow to reduce no-shows.

Deployment Instructions:

Import JSON: Open n8n, click 'Import from File' and select dental-automation-v1.json.

Credentials: Connect your Twilio (WhatsApp), OpenAI, and Google Calendar accounts.

Environment Variables:

CLINIC_NAME: "Your Clinic Name"

REVIEW_LINK: "Your Google Review URL"

Webhook URL: Copy the Production Webhook URL from the first node and paste it into your VoIP provider's 'Missed Call' settings.