🌌 COSMOS — Universe Messenger

Real-time space-themed chat where group conversations become solar systems floating in an infinite, explorable universe.

<img width="92" height="18" alt="image" src="https://github.com/user-attachments/assets/bc2375ea-5c29-4aa7-b86a-439f38a03f31" />
<img width="476" height="456" alt="image" src="https://github.com/user-attachments/assets/ceb49b56-e2cd-4585-b68a-0d9becbe0fc2" />
🌌 COSMOS — Universe Messenger

    Real-time space-themed chat where group conversations become solar systems floating in an infinite, explorable universe.

🚀 Live Demo

https://mdshameel.github.io/cosmos-messenger/
✨ Features

    🌟 Solar Systems — Create communities that appear as glowing suns in infinite space
    🪐 Group Chats — Groups orbit their parent system as planets in real time
    💬 Live Messaging — WhatsApp-style real-time chat powered by Supabase
    🔗 Invite Codes — Every system and group gets a unique 8-character code to share
    🟢 Online Presence — See who's online, send direct messages privately
    ⏱ Auto-Delete — Public group messages delete after 24 hours automatically
    👑 Admin Controls — Creators can remove members from their systems/groups
    🧑 Custom Profiles — Change your name and avatar anytime
    🗺 Infinite Universe — Drag, zoom, and explore an ever-expanding space canvas
    🌌 Parallax Stars — 4-layer star field with nebulae and twinkling effects

🛠 Tech Stack
Layer	Technology
Frontend	Vanilla HTML, CSS, JavaScript
Backend	Supabase (PostgreSQL + Realtime)
Hosting	GitHub Pages
Fonts	Orbitron, Space Grotesk (Google Fonts)
📦 Setup
1. Clone the repo
bash

git clone https://github.com/mdshameel/cosmos-messenger.git
cd cosmos-messenger

2. Set up Supabase

    Create a free project at supabase.com
    Run the SQL from cosmos_schema.sql in the Supabase SQL Editor
    Copy your Project URL and anon public key

3. Configure credentials

Open index.html and update these two lines:
js

const _BAKED_URL = 'YOUR_SUPABASE_URL';
const _BAKED_KEY = 'YOUR_SUPABASE_ANON_KEY';

4. Deploy

Push to GitHub and enable GitHub Pages from Settings → Pages → Deploy from main branch.
🗄 Database Schema

Run cosmos_schema.sql to create all required tables:

    systems — Solar system communities
    groups — Chat groups orbiting a system
    members — User memberships
    messages — Group chat messages (auto-deleted after 24h in public groups)
    direct_messages — Private 1-on-1 messages
    presence — Online user tracking

📁 Project Structure

cosmos-messenger/
├── index.html          # Entire app (self-contained)
├── cosmos_schema.sql   # Supabase database setup
├── README.md
├── LICENSE
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── SECURITY.md

🤝 Contributing

Contributions are welcome! Please read CONTRIBUTING.md first.
📄 License

MIT License — see LICENSE for details.
🔒 Security

Found a vulnerability? See SECURITY.md for responsible disclosure.

Built with ❤️ by mdshameel
