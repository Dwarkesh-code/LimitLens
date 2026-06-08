# Claude Usage Tracker or LimitLens

A lightweight, real-time browser extension to monitor your Claude.ai session limits and context window usage.

Are you a power user constantly hitting Claude's message limits? Claude Usage Tracker is a zero-overhead browser extension that injects directly into the Claude.ai interface to give you real-time insights into your session consumption, context window usage, and server traffic (Peak/Off-Peak). 

Never get caught off-guard by the message limit warning again.

## Features

* Real-Time Session Tracking: Monitor your exact message limit consumption as a dynamic percentage. Updates instantly as you chat, without requiring page refreshes.
* Context Window Monitoring: Keep an eye on how much of the context window your current chat is utilizing. 
* Peak Hours Indicator: Instantly know if Claude's servers are experiencing high traffic (Peak vs Off-Peak), which affects your message limits.
* Session History Logging: Automatically logs your recent sessions and usage statistics right within the extension popup.
* Native UI Integration: Injects a clean, non-intrusive progress bar UI seamlessly into the Claude chat interface.

## Installation Guide (Developer Mode)

Currently, this extension is available via manual installation:

1. Download the code or the pre-compiled `chrome_edge_extension.zip` from the `dist` folder.
2. Unzip the downloaded file to a folder on your computer.
3. In your browser, navigate to `chrome://extensions/` (for Chrome) or `edge://extensions/` (for Edge).
4. Toggle the "Developer mode" switch in the top right corner.
5. Click the "Load unpacked" button in the top left and select the folder you extracted.
6. Pin the extension to your browser toolbar.

## Architecture & Privacy

This extension is built with Manifest V3 and uses Vanilla JavaScript for maximum performance. It operates completely locally. There are no tracking pixels, no analytics, and no remote servers. Your chat data never leaves your browser. The extension only reads network responses related to usage limits strictly within the browser context.

## About the Author

Built by Dwarkesh. This entire project was architected and developed using "Vibe Coding" (AI-assisted programming). The logic, structure, and design were created completely through advanced prompt engineering, showcasing the power of modern AI workflows.

GitHub: [@Dwarkesh-code](https://github.com/Dwarkesh-code)
