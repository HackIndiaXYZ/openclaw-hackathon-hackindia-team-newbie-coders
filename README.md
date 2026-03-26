# openclaw-hackathon-hackindia-team-newbie-coders
Hackathon team repository for Team Newbie Coders - [hackindia-team:openclaw-hackathon-hackindia:team-newbie-coders]

Team Name - Newbie Coders
Team Members - Harsh Garg, Hardik Sharma, Gaurav Chauhan, Gaurav Yadav
Project Name - Guardian Link
Guardian Link is a public safety system designed to protect users in distress situations. It leverages AI-powered wake-word detection, automated evidence collection, and multi-channel alert distribution to ensure timely help.
Project Link - https://gargharsh565-newbie-coders-build-for-07ip.onrender.com

🔑 Core Features
- SOS Activation (Wake Word)
- AI model continuously listens in background (if permitted).
- Triggered automatically when user says distress keywords like “help”, “bachao”, or any custom keywords added in settings.
- Works like a wake word system (“Hey Google” → Google Assistant).
- Manual SOS button also available.
- Contextual Distress Detection: AI also analyzes tone of voice (panic, shouting, crying) to trigger SOS.
- Multi-Language Support: Distress keywords and SOS messages support local languages (e.g., Hindi “bachao”) for broader accessibility.
- Silent Trigger Mode: Allow activation with subtle phrases or gestures (e.g., pressing volume buttons in a pattern) for situations where speaking keywords isn’t safe. Configurable in settings.
- Evidence Collection
- Rear camera image.
- Front camera image.
- Audio recording via microphone.
- Location (Google Maps link).
- Evidence refreshed every 5 minutes until SOS is manually turned off.
- Encrypted Evidence Transmission: All images, audio, and location data are encrypted before being sent to ensure privacy and security.
- SOS Messaging
- Sends evidence + custom SOS message to:
- SMS
- WhatsApp
- Discord (via webhook)
- Telegram (via bot token + chat ID)
- Continuous cycle: SOS messages are sent every 5 minutes with freshly captured images, audio, and location until the user manually deactivates SOS with a password.
- SOS Deactivation
- Requires password authentication.
- Password can be set/changed in settings.
- Emergency Loud Alarm
- Option to play a loud siren sound manually when SOS is triggered to attract nearby attention.
- Manual activation ensures attackers are not alerted prematurely.
- Configurable alarm type (siren, whistle, custom audio).
- Tamper Detection
- If someone tries to uninstall or disable Guardian Link, the app immediately notifies the user’s emergency contacts.

⚙️ Settings Menu
- Run in Background: Enable/disable app background execution (needed for wake word detection).
- Emergency Loud Alarm: Toggle on/off, choose alarm type and volume.
- Silent Trigger Mode: Configure subtle activation gestures or phrases.
- Customize SOS message content.
- Choose which evidence types to collect.
- Configure recipients (contacts, Discord webhook, Telegram bot).
- Manage distress keywords (add/remove custom wake words).
- Set/change SOS deactivation password.

👥 Contact Management (Network Tab)
- Emergency Contacts (“My Circle”): Add/remove contacts with name, phone, relation.
- Discord Webhook Config: Save and manage webhook URL.
- Telegram Bot Config: Save and manage bot token + chat ID.

📋 Alert History
- View all past emergency alerts with timestamps.
- Display channels used and delivery status.
- Photo Evidence Display: Side-by-side thumbnails (front cam / rear cam).
- Audio Playback: Replay recorded audio evidence.

Note - The Current project is a prototype version that may lack few features.
