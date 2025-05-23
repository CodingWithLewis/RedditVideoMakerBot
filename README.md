# Reddit Video Maker Bot ✨

An automated solution for creating Reddit story videos for social media platforms like TikTok, YouTube, and Instagram.

https://user-images.githubusercontent.com/66544866/173453972-6526e4e6-c6ef-41c5-ab40-5d275e724e7c.mp4

The bot takes a Reddit thread, converts the comments to speech, adds a background video, and compiles everything into a ready-to-upload video for platforms like TikTok, YouTube, and Instagram.

## Overview

This bot automatically creates videos from Reddit posts and comments without requiring video editing skills. It handles text-to-speech conversion, background selection, and video compilation.

## Requirements

- Python 3.10+
- Playwright (installed during setup)

## Installation

1. Clone this repository
   ```
   git clone https://github.com/elebumm/RedditVideoMakerBot.git
   cd RedditVideoMakerBot
   ```

2. Install dependencies
   ```
   pip install -r requirements.txt
   python -m playwright install
   python -m playwright install-deps
   ```

3. Run the bot
   ```
   python main.py
   ```

4. Set up Reddit API access
   - Visit [Reddit Apps page](https://www.reddit.com/prefs/apps)
   - Create a new app (select "script" type)
   - Enter any URL for the redirect URL
   - Follow the bot's prompts to enter your API credentials

## Configuration

- The bot will guide you through configuration on first run
- To reconfigure, edit or delete lines in `config.toml`
- For detailed instructions, see the [documentation](https://reddit-video-maker-bot.netlify.app/)

## Features

- Text-to-speech narration with multiple voice options
- Customizable background videos
- Support for any subreddit
- Light and dark mode themes
- NSFW content filtering
- Manual or random Reddit thread selection

## Contributing

Contributions are welcome! Please read our [contributing guidelines](CONTRIBUTING.md) for more information.

## Support

For questions or support, join our [Discord server](https://discord.gg/qfQSx45xCV).

## License

[Roboto Fonts](https://fonts.google.com/specimen/Roboto/about) are licensed under [Apache License V2](https://www.apache.org/licenses/LICENSE-2.0)
