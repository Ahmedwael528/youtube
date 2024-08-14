# 🎬 YouTube Video Downloader

## 🌐 Overview
This script allows you to download YouTube videos using the Pytube library. It reads a list of YouTube video URLs from a file (`urls.txt`) and attempts to download each video in the highest resolution possible (720p, 480p, or 360p with audio)also able to download whole youtube playlist.

## ✅ Prerequisites
- Run `pip install requirements.txt`

## ✨ Usage

### 🔹 Download list of videos
1. Create a text file named `urls.txt` in the same directory as the script.
2. Add one YouTube video URL per line in the `urls.txt` file.
3. Run the script using the command `python downloader.py` in your terminal or command prompt.

### 🔹 Download a playlist
1. Run the script using the command `python playlist.py` in your terminal or command prompt.
2. Enter the playlist URL when prompted.

## 📤 Output
- Downloaded videos will be stored in the 'Youtube_Videos' folder in the script's directory.
- The script will remove successfully downloaded video URLs from the `urls.txt` file.
- If an error occurs during the download, the script will print an error message and continue to the next video.

## 🖊️ Note
- If the 'Youtube_Videos' folder does not exist, the script will create it.
- The script prioritizes downloading videos in the following resolutions: 720p, 480p, and 360p with audio.
- If a video cannot be downloaded due to an error, the error message will be displayed, and the script will proceed to the next video.

## 🖥️ Author
Weloo00

