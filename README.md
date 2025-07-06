# Video To Audio
## 📝 Description
A simple Python script to convert video files (e.g., `.mp4`) into audio files (e.g., `.mp3`) using the `MoviePy` library.

## 📥 Input
- Any video file supported by MoviePy/FFmpeg (e.g., `.mp4, .avi, .mov`)

- Example:

      convert_video_to_audio_moviepy("test.mp4")
  
## 📤 Output
- Extracted audio file in the format of your choice (default: `.mp3`)

- Example output: `test.mp3`

## 🚀 Features
- Converts video files to audio with just one function call

- Supports multiple audio formats like `.mp3, .wav`, etc.

- Lightweight and easy to customize

## 🧠 Technologies Used
- Python 3

- MoviePy (built on top of FFmpeg)

- FFmpeg (must be installed on your system)

## 🔧 How to Use
1. Install the required package:

       pip install moviepy

2. Make sure FFmpeg is installed
(MoviePy uses FFmpeg internally. Install from https://ffmpeg.org/ if needed)

3. Run the script:

       convert_video_to_audio_moviepy("your_video.mp4")
4. Result: You’ll get an audio file like your_video.mp3 in the same directory.
