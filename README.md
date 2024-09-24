# YouTube Video Playback Control System

This project is a video playback control system that utilizes the YouTube IFrame Player API. It tracks the playback status (playing or paused) and displays both the current playback time and the total duration of the video.

## Features
- Control video playback (play/pause)
- Display current playback time
- Display total video duration

## Getting Started

### Prerequisites
- A web browser to view the HTML file.
- A local web server (e.g., Python's HTTP server, XAMPP, or similar) to serve the HTML file.

### Usage
1. Clone this repository to your local machine using:
   ```bash
   git clone https://github.com/yourusername/repository-name.git
2. Navigate to the cloned directory.
3. Start a local web server. For example, using Python:
   ```bash
   python -m http.server 8000
4. Open your web browser and go to http://localhost:8000/index.html.

### Modifying the Video
To change the embedded video, update the `videoId` variable in the `<script>` section of the `index.html` file:
   ```javascript
   videoId: 'your_new_video_id',
   ```

## License
This project is licensed under the GNU General Public License v3.0 (GPL-3.0).
