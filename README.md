# **Traducao - Automatic Subtitle Generator**

**Traducao** is a multifunctional media conversion website that provides subtitle generation, offline video translation, and text-to-speech (TTS) services. Primarily leveraged for subtitle translation on YouTube, it helps content creators automatically generate subtitles and translate them into multiple languages, enhancing accessibility for diverse audiences.

---

## **Table of Contents**

- [About the Project](#about-the-project)
- [Key Features](#key-features)
- [Tech Stack](#tech-stack)
- [Project Setup](#project-setup)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## **About the Project**

Traducao helps users generate and translate subtitles for YouTube videos and other multimedia files. By integrating Google's translation services and speech recognition, it ensures high accuracy in both audio extraction and translation. The platform is designed to attract 1,000+ users in its first year and handle up to 500 video and 1,500 audio file conversions annually.

### **Use Case**
The platform mainly targets content creators on YouTube, allowing them to automatically generate and translate subtitles, expanding their audience reach to non-native speakers.

---

## **Key Features**

- **Automatic Subtitle Generation:** Fetches subtitles from YouTube videos and generates them automatically using speech-to-text services.
- **Offline Video Translator:** Supports subtitle translation in multiple languages for locally uploaded videos.
- **Text-to-Speech Services:** Converts text into speech, enabling users to download audio files.
- **Audio Extraction:** Extracts and converts audio from video files to various formats.
- **YouTube Integration:** Fetches subtitles and audio directly from YouTube links for easy conversion and translation.

---

## **Tech Stack**

### **Frontend:**
- JavaScript
- HTML5
- CSS
- Bootstrap

### **Backend:**
- Flask
- Python (with gTTS, Pyttsx3, MoviePy, SpeechRecognition libraries)

### **APIs & Libraries:**
- Google Translator API (language translation)
- YouTube Transcript API (fetching subtitles)
- Pytube (downloading YouTube videos)

### **Database:**
- SQLite (storing user data and media conversion logs)

---

## **Project Setup**

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/Traducao.git
   cd Traducao
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask app:**
   ```bash
   python app.py
   ```

4. **Access the app on your browser:**
   Open `http://localhost:5000` in your web browser.

---

## **Usage**

1. **Home Page:** Provides links to various tools such as video/audio translation and subtitle generation.
2. **Subtitle Generation:** Enter a YouTube video URL to generate subtitles and translate them.
3. **Audio Extraction:** Extract audio from YouTube videos or upload local video files to extract and convert audio.
4. **Offline Video Translator:** Translate audio in video files into various languages using Google Translate.
5. **Text-to-Speech:** Enter text, select a language, and convert it into spoken audio, which can be downloaded as a file.

---

## **File Structure**

```plaintext
Traducao/
│
├── templates/             # HTML templates
│   ├── homepagemain.html
│   ├── tool1.html
│   ├── tool2.html
│   ├── tool3.html
│   ├── tool4.html
│   ├── tool5.html
│   ├── contact.html
│   ├── about_us.html
│   └── ...                # Other templates
│
├── static/                # Static files (CSS, JavaScript, Images)
│
├── app.py                 # Main Flask application
│
├── requirements.txt       # Required libraries
│
└── README.md              # Project documentation (this file)
```

---

## **Contributing**

We welcome contributions to enhance the functionality of Traducao. Here's how you can contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/YourFeature
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m "Added new feature"
   ```
4. Push to the branch:
   ```bash
   git push origin feature/YourFeature
   ```
5. Open a pull request.

---

## **License**

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## **Contact**

- **Email:** karanamsruthi17@gmail.com
- **GitHub:** [sruthi-karanam](https://github.com/sruthi-karanam)
- **LinkedIn:** [Sruthi Karanam](https://www.linkedin.com/in/karanam-sruthi-a08412255/)

---

