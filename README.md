# Rank-Twitch-Chat-Spam `Emote support for 7TV only`. 

`Pefect for when you don't want polls or polls are not fast enough.` 

A real-time, browser-based dashboard that tracks and ranks the most spammed words and 7TV emotes in any Twitch chat.

## Usage

1.  **Open the App:** [Click here to view live demo](https://gamerboyrts-a11y.github.io/Rank-Twitch-Chat-Spam/)
2.  **Enter Channel:** Type a channel name (e.g., `xqc`, `forsen`, `Gorgc`) and hit **Connect**.
3.  **Watch:** The board will light up with the top spammed emotes in real-time.
4.  **Customize:**
    -   Toggle **"Show Emotes Only"** to see text spam vs. emote images.
    -   Adjust the **Reset Timer** (default 30s) to change how often the board clears.

![alt text](https://github.com/gamerboyrts-a11y/Twitch-Chat-spam/blob/0e871365d3e201309adb4d01fefe2fca3be2aeb1/Web.png "Website")

## Features

-   **Live Tracking:** Connects anonymously to Twitch chat (IRC) instantly via WebSocket.
-   **Top 3 Leaderboard:** Visualizes the top 3 trending items with live progress bars.
-   **7TV Emote Support:** Automatically fetches and displays 7TV emotes for the connected channel.
-   **Smart Filtering:** 
    -   **"Show Emotes Only"** toggle (On by default) to filter out text/number spam.
    -   Intelligent decay algorithm ensures only *currently* trending spam is shown.
-   **Auto-Reset:** Built-in timer (default 30s) clears the board automatically to keep trends fresh.
    -   **Customizable:** Set to any duration (e.g., 10s, 60s).
-   **No Login Required:** Works anonymously; no Twitch account or API keys needed.


## Installation / Hosting

This is a static web application (HTML/JS/CSS). You can host it anywhere.

## Technologies

-   **Vanilla JavaScript (ES6+)** - No frameworks, lightweight single-file application.
-   **WebSockets** - For real-time Twitch IRC connection.
-   **7TV API** - For fetching channel-specific emote data.
-   **IVR API** - For resolving Twitch usernames to IDs without OAuth.

## License

MIT License - feel free to modify and use!
