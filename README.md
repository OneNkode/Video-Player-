✨ Features
Modern UI: Minimalist design with clean and responsive layouts.
Comprehensive Playback Controls:
Play, Pause, Stop, and Seek functionality.
Interactive seek bar for precise navigation.
Dynamic Resizing: Videos automatically adapt to the canvas size while maintaining aspect ratio.
Error Handling: User-friendly messages for unsupported or invalid video files.
Thread-Safe: Smooth playback without freezing the UI.
Multi-Format Support: Compatible with .mp4, .avi, .mov, and more (via OpenCV and ffmpeg).
🛠️ Installation
Clone the repository:

bash
Kód másolása
git clone https://github.com/your-username/modern-video-player.git
cd modern-video-player
Install the required dependencies:

bash
Kód másolása
pip install -r requirements.txt
Dependencies:

opencv-python
Pillow
Run the application:

bash
Kód másolása
python video_player.py
📚 Usage
Click on 📂 Open to load a video file.
Use the playback controls:
▶ Play: Start the video.
⏸ Pause: Pause the video.
⏹ Stop: Stop the video.
Drag the seek bar to jump to a specific point in the video.
🐛 Known Issues
Playback Performance: Videos with very high frame rates may experience slight delays.
Unsupported Formats: Ensure ffmpeg is installed and in your system's PATH to support all common video codecs.
🗓️ Roadmap
Add support for subtitles (e.g., .srt files).
Enable audio volume control.
Include a fullscreen toggle option.
Build an installer for non-developers.
🤝 Contributing
Contributions are welcome! Feel free to open issues or submit pull requests. Check the Contributing Guide for more details.

📄 License
This project is licensed under the MIT License. See the LICENSE file for details.

💡 Acknowledgments
Built using Python, OpenCV, and Tkinter.
Inspired by modern video playback applications.
