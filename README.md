# YouTube1080p Downloader

This Python script allows you to download YouTube videos in 1080p quality (or the best available quality up to 1080p) using the yt-dlp library.

## Features

- Downloads YouTube videos in up to 1080p quality
- Combines the best video and audio streams
- Outputs the video in MP4 format
- Handles errors and provides detailed error information

## Requirements

- Python 3.x
- yt-dlp library
- FFmpeg (for video conversion and merging)

## Installation

1. Ensure you have Python 3.x installed on your system.
2. Install the required library using pip:
pip install yt-dlp

3. Install FFmpeg on your system. You can download it from the [official FFmpeg website](https://ffmpeg.org/download.html).

## Usage

You can run the script in two ways:

1. Provide the YouTube URL as a command-line argument:
python YouTube1080p.py https://www.youtube.com/watch?v=VIDEO_ID

2. Run the script without arguments and enter the URL when prompted:
python YouTube1080p.py


The script will download the video and save it in the current directory with the video's title as the filename.

## How it works

1. The script uses yt-dlp to extract video information and download the best quality video (up to 1080p) and audio streams separately.
2. It then uses FFmpeg to merge the video and audio streams into a single MP4 file.
3. The final video is saved with the original video title as the filename.

## Error Handling

If an error occurs during the download process, the script will print:
- The error message
- The type of error
- Detailed error information

This helps in diagnosing and troubleshooting any issues that may arise during the download process.

## Disclaimer

Please ensure you have the right to download and use the video content. Respect copyright laws and YouTube's terms of service.
