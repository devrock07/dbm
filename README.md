# Discord Activity Toolkit

A lightweight Python toolkit for experimenting with Discord activity tracking, voice connections, media streaming, and profile information.

## Features

- **Game Activity:** Tools for working with game activity events.
- **Media Streaming:** Local video and audio streaming through voice connections.
- **Voice Gateway:** WebSocket-based voice connection handling.
- **Profile Inspection:** View Discord profile information and available badges.
- **Session Management:** Shared configuration and session handling.
- **Cross-Platform:** Designed for Python 3.10 and newer.

## Requirements

- Python 3.10+
- FFmpeg (for media streaming)
- Dependencies listed in `requirements.txt`

## Installation

```bash
git clone YOUR_REPOSITORY_URL
cd YOUR_PROJECT
pip install -r requirements.txt
```

## Usage

Run the desired module:

```bash
python games.py
```

```bash
python stream.py
```

Follow the on-screen instructions to configure and run the available features.

## Security

- Never share your Discord authorization credentials.
- Keep session files private.
- Use supported Discord interfaces and respect Discord's Terms of Service.
- Do not use automated activity reporting to misrepresent account activity.

## Disclaimer

This is an independent, experimental project and is not affiliated with or endorsed by Discord Inc.

## License

Released under the MIT License.
