# **Traducao - Automatic Subtitle Generator**

Traducao is a web-based tool designed for automatic subtitle generation and translation. The application leverages various APIs and technologies to provide a comprehensive suite of functionalities for handling video and audio content. 

## **Features**

- **YouTube Transcript Translation**: Automatically generates and translates transcripts from YouTube videos.
- **YouTube Video Downloader**: Downloads YouTube videos for offline access.
- **YouTube Audio Extractor**: Extracts audio from YouTube videos.
- **Offline Video Translation**: Translates audio from offline video files.
- **Audio File Translation**: Translates audio files to text.
- **Text to Speech**: Converts text input to spoken audio.
- **Speech to Text**: Converts spoken audio into text.

## **Installation**

### **Prerequisites**

Make sure you have the following installed:

- Python 3.x
- Flask
- Required Python libraries

### **Clone the Repository**

```bash
git clone https://github.com/your-repository-url.git
cd your-repository-directory
```

### **Create a Virtual Environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### **Install Dependencies**

Create a `requirements.txt` file with the following content:

```
Flask
gtts
playsound
pyttsx3
moviepy
youtube_transcript_api
speech_recognition
pytube
googletrans==4.0.0-rc1
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

## **Usage**

### **Running the Application**

Start the Flask server:

```bash
python app.py
```

Access the application in your web browser at `http://localhost/`.

### **Endpoints**

- **Home**: `/` - Displays the main page.
- **YouTube Transcript Translation**: `/ltt` - Extracts and translates transcripts from YouTube videos.
- **YouTube Video Downloader**: `/yvd` - Downloads videos from YouTube.
- **YouTube Audio Extractor**: `/ae` - Extracts audio from YouTube videos.
- **Offline Video Translation**: `/ovt` - Translates audio from offline videos.
- **Audio File Translation**: `/aft` - Converts audio files to text.
- **Text to Speech**: `/tts` - Converts text to speech.
- **Speech to Text**: `/att` - Converts speech to text.
- **Contact Us**: `/contact_us` - Contact form for user inquiries.
- **About Us**: `/abs` - Information about the project.

### **Example Usage**

1. **Translate YouTube Transcript**:
   - Navigate to `/ltt`.
   - Enter the YouTube video link and select the target language.
   - Submit to get the translated transcript.

2. **Download YouTube Video**:
   - Go to `/yvd`.
   - Provide the YouTube video URL and download the video.

3. **Convert Text to Speech**:
   - Visit `/tts`.
   - Input the text and submit to generate the speech output.

## **Development**

To contribute to this project:

1. **Fork the Repository**.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature-branch
   ```
3. **Commit Your Changes**:
   ```bash
   git commit -am 'Add new feature'
   ```
4. **Push to the Branch**:
   ```bash
   git push origin feature-branch
   ```
5. **Create a New Pull Request**.

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## **Acknowledgments**

- [Flask](https://flask.palletsprojects.com/) for the web framework.
- [gTTS](https://gtts.readthedocs.io/en/latest/) and [pyttsx3](https://pyttsx3.readthedocs.io/en/latest/) for text-to-speech conversion.
- [MoviePy](https://zulko.github.io/moviepy/) for video and audio processing.
- [YouTube Transcript API](https://github.com/jdepoix/youtube-transcript-api) for transcript extraction.
- [Speech Recognition](https://pypi.org/project/SpeechRecognition/) for speech-to-text.
- [Pytube](https://pytube.io/) for YouTube video downloading.
- [Google Translate](https://pypi.org/project/googletrans/) for language translation.

---

