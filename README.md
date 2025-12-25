## Rank-Twitch-Chat-Spam

  The Ultimate Real-Time Chat Meter.
  Perfect for when you don't want polls or polls are not fast enough.

A powerful, browser-based dashboard that tracks, ranks, and visualizes the most spammed words and emotes in any Twitch chat in real-time. Designed specifically for streamers and OBS overlays.

[Click here to view live demo](https://gamerboyrts-a11y.github.io/Rank-Twitch-Chat-Spam/)


Twitch Spam Tracker Screenshot**![alt text](https://github.com/gamerboyrts-a11y/Rank-Twitch-Chat-Spam/blob/7297b016660456ce38546b4b2d1887f62206b7d9/Web.png "Website")

✨ Features
🎨 Visual & Interactive

    Live Leaderboard: Visualizes the top trending spam with animated progress bars.
    Dynamic Card Count: Choose how many top items to display (Top 3, Top 5, Top 10, etc.).
    Hype Mode (Combo Animation): Cards pulse gold/glow when spam speed hits critical mass (10+ hits in 5s).
    Live Velocity Graph: A real-time line chart showing "Chat Velocity" (Messages per Second).

🛠️ OBS & Streamer Tools

    OBS Transparent Mode: One-click toggle to make the background transparent and hide controls for seamless OBS overlay.
    Pop-out Window: Instantly opens the tracker in a clean, borderless popup window (removes browser tabs/address bar).
    Auto-Save Settings: Remembers your channel, timer, blacklist, and layout settings automatically.

🤖 Emote & Spam Intelligence

    Universal Emote Support:
        ✅ Twitch (Global & Channel)
        ✅ 7TV (Global & Channel)
        ✅ BetterTTV (BTTV) (Global & Channel)
        ✅ FrankerFaceZ (FFZ) (Global & Channel)
        ✅ Emoji Support (🔥, 😂, 💀)

    Smart Filters:
        "Show Emotes Only": Toggle to ignore text and focus purely on emote spam.
        Blacklist: Built-in filter for common stop words ("the", "is", "a") + Custom user-defined blacklist.
        Unique Filter: Count spam only once per message (prevents one user from artificially inflating count).
        User Cooldown: Prevents a single user from spamming the counter (default 10s cooldown per word per user).

📖 How to Use (For OBS)

    Open the App: Go to the Live Demo.
    Connect: Enter a channel name (e.g., xqc, kaicenat) and hit Connect.
    Pop-out: Click the "Pop-out" button to open a clean window.
    OBS Mode: In the new window, click "Toggle OBS Mode".
    This makes the background transparent and hides all buttons.
    Add to OBS: Use Window Capture in OBS to select the popup window.
    Tip: Use "Allow Transparency" in OBS capture properties if available.
    To Exit OBS Mode: Double-click anywhere on the transparent page.

⚙️ Customization

    Setting	Description
    Window (s)	How long (in seconds) to count spam before it decays/resets.Default is 30s.
    Max Cards	Number of rank cards to display (Default: 3).
    Show Emotes Only	Hides text words, showing only valid emotes or emojis.
    Unique per Msg	If ON, typing "LUL LUL LUL" counts as +1 score instead of +3.
    User Cooldown	If ON, ignores the same word from the same user for X seconds.
    Edit Blacklist	Add custom words to ignore (e.g., bot commands like !discord).

💻 Installation / Hosting

    This is a static web application (HTML/JS/CSS). 
    It requires no backend server.
    Download: Download index.html.
    Run: Open it directly in Chrome/Edge/Firefox.
    Host: Upload to GitHub Pages.

🛠️ Technologies

    Vanilla JavaScript (ES6+) - Zero framework bloat.
    WebSockets - Direct connection to Twitch IRC (Anonymous, no login required).
    Chart.js - Lightweight library for the velocity graph.
    IVR API - Resolves Twitch usernames to IDs.
    Emote APIs - 7TV, BTTV, and FFZ public APIs.

## License

MIT License - feel free to modify and use!
