# YouTube Transcript Downloader

This GitHub repository contains a Python notebook designed to download YouTube video transcripts automatically. It's a handy tool for users who need to fetch transcripts from multiple videos, particularly for content analysis, data mining, or accessibility purposes.

## Features

- **Channel Video URL Fetching**: Fetches all video URLs from a given YouTube channel.
- **Transcript Download**: Downloads transcripts for each video URL.
- **Error Handling**: Gracefully handles videos without available transcripts.
- **File Management**: Saves transcripts to local files and archives them for easy download.

## Installation

Before running the notebook, you need to install the required packages. Run the following commands:

```bash
!pip install youtube-transcript-api
!pip install google-api-python-client
```

## Usage

1. **Set up API Key and Channel ID**: Replace the `api_key` and `channel_id` variables with your YouTube Data API key and the desired channel ID.
2. **Run the Notebook**: Execute the cells to fetch video URLs, download transcripts, and save them.
3. **Transcript Files**: Transcripts are saved in a specified directory, each named after the corresponding video ID.
4. **Archiving**: After downloading, the transcripts are archived into a zip file for easy download and removal from the workspace.

## Components

- **YouTube API Integration**: Uses the YouTube Data API to fetch video details.
- **Transcript Extraction**: Leverages the `youtube-transcript-api` package to obtain transcripts.
- **File Operations**: Python's file handling capabilities are used for saving transcripts and managing directories.

## Requirements

- Google API key with YouTube Data API enabled.
- YouTube channel ID from which you want to fetch video URLs.
- Python environment (like Jupyter Notebook) to run the code.

## Disclaimer

This tool is intended for legitimate purposes like research, content accessibility, and personal use. Please respect copyright laws and YouTube's terms of service while using it.

## Contributing

Contributions, bug reports, and feature requests are welcome! Please read our contributing guidelines and code of conduct before submitting your pull requests.

---

**Note**: The provided API key and channel ID in the notebook are placeholders. Replace them with your valid API key and desired channel ID. Also, ensure you comply with YouTube's API usage limits and guidelines.

---

This project is open-source and not affiliated with YouTube or Google.
