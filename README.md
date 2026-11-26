# Mindanchor-
MindAnchor is a student demo web app for dementia care. It offers a patient home with calm dialogues, voice reminders and a simulated two-step SOS, plus a caregiver view with status, simulated location sharing and read-only fictional records. Uses invented data only; not a medical or emergency service.
🧠 MindAnchor

A student demonstration web app exploring technology-assisted dementia care.
📖 About

MindAnchor shows how a simple, calm interface could support a person living with dementia and their caregiver. It focuses on clear communication, gentle reminders, and giving caregivers quick access to status and guidance. It is built as a single-page, responsive web interface with simulated data.

✨ Features
🏠 Patient Home
Large, simple view showing identity ("I am Maya Patel"), location status, last check-in, and battery (all demo values)
One-tap actions: Play reminder, I'm okay, Call caregiver
Calm support dialogues: respectful phrases that can be spoken aloud
Two-step SOS simulation with confirmation, timestamp, and cancel option (no call or message is sent)
👩‍⚕️ Caregiver Area
Password-free demo role switch (illustrative only, not real authentication)
Patient status view (Safe / Needs check-in / SOS active) with suggested next actions
Guided actions: request check-in, send reminder, start calm dialogue, review alert history
Simulated location sharing (not live GPS) with start, pause, and stop controls
Demo activity log and alert history
📁 Records (Fictional)
Access gate that requires the caregiver demo session
Categories: Overview, Medications, Allergies, Appointments, Care Notes, Documents, Activity Log
Search across fictional entries
Read-only caregiver view, with disabled administrator-only controls to illustrate role separation
"Explain for judges" panel describing the intended production design
🔊 Voice Helper
Preview short spoken reminders (identity, hydration, medication, orientation) using the browser's built-in speech synthesis
Schedule timed reminders by type, date, time, and repeat pattern (once, daily, weekdays, custom days)
Demo-only delivery targets (this device or a simulated connected phone). Schedules only run while the page is open.
🎬 Storyboard
A built-in six-scene, 5-minute demo walkthrough with a presenter checklist
🛠️ Built With
HTML, CSS, and JavaScript (single index.html file)
Tailwind CSS (CDN)
Lucide icons
Browser Web Speech API (speechSynthesis) for voice previews
Google Fonts (Work Sans)
🚀 Getting Started
Clone the repository:
bash
git clone https://github.com/your-username/mindanchor.git
Open index.html in any modern browser. No build step or server needed.
Use the Demo reset button at any time to restore the initial state.

Internet access is needed for the CDN-hosted fonts and libraries.

🔒 Privacy & Safety Plan (Future Work)

This prototype does not connect to real authentication, storage, alerts, or location services. A production version would require:

Firebase Authentication and Storage (or equivalent) with server-enforced access rules
Explicit user consent and secure data transport
Genuine audit logging
Mobile pairing, notification permissions, and a backend notification service
Clinical review and compliance with applicable healthcare regulations
Patient device → MindAnchor web app → planned Firebase Auth & Storage → Caregiver dashboard
🗺️ Roadmap
[ ] Real authentication and role-based access control
[ ] Secure cloud storage for care documents
[ ] Real push notifications and mobile reminders
[ ] Opt-in live location sharing
[ ] Clinician and caregiver feedback and usability testing
👤 Author

Ankit Mukherjee, first-year B.Tech Engineering student, working on a medtech project focused on dementia.

📄 License

This project is for educational and demonstration purposes. Add a license of your choice (for example, MIT) before sharing publicly.
