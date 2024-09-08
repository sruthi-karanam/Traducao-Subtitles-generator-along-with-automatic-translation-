# Automatic_Subtitle_Generator
Project Name: Traducao - Automatic Subtitle Generator
Description:
Traducao is a multifunctional media conversion website primarily used for generating automatic subtitles for YouTube videos. The platform also supports offline video translation, audio extraction, and text-to-speech (TTS) services. Users can easily translate subtitles into multiple languages, aiding in accessibility and international reach for content creators. The app allows for subtitle generation and translation directly from YouTube links, as well as offline media files. It integrates Google's translation services and speech recognition technologies to ensure high accuracy in both audio extraction and translation. The platform is strategized to attract over 1,000+ users in its first year, handling up to 500 video conversions and 1,500 audio file conversions annually.

Key Features:
Offline Video Translator: Translate video subtitles in multiple languages, making it accessible for various audiences.
Text-to-Speech Services: Convert translated text into speech in different languages and download audio files.
Automatic Subtitle Generation: Generates subtitles automatically for videos, leveraging speech-to-text services.
YouTube Integration: Fetch and translate subtitles for YouTube videos directly through URL input.
Audio Extraction: Extract audio from video files, convert them into various formats, and enable translations.
Use Case:
The platform is especially beneficial for subtitle generation and translation on YouTube videos, allowing content creators to reach a broader, multilingual audience.

Tools & Technologies Used:
Frontend:

React.js
HTML5
CSS
Bootstrap
Backend:

Flask
Python (including libraries like gTTS, Pyttsx3, MoviePy, SpeechRecognition)
APIs & Libraries:

Google Translator API (for language translation)
YouTube Transcript API (for fetching subtitles)
Pytube (for downloading YouTube videos)
Database:

SQLite (for storing user data, logs, and media conversion data)
Code Functionality:
Home Page: The main landing page, which directs users to various functionalities like video and audio conversion.
Subtitle Generation: Fetches YouTube videos and uses the YouTubeTranscriptApi to extract transcripts, then translates the subtitles using Google Translate.
Audio Extraction: Extracts audio from YouTube videos and converts them into downloadable MP3 files.
Offline Video Translation: Supports uploading local video files, converts their audio into text, and translates it into the desired language using Google's services.
Text-to-Speech: Converts entered text into spoken audio using pyttsx3 or gTTS libraries and plays the sound on the website.
Contact Us Page: A simple form to allow users to contact the platform administrators.
Project Strategy:
Traducao aims to cater to a growing user base, targeting 1,000+ users in its first year by providing seamless multimedia services for content creators and language enthusiasts. The platform is engineered to handle 500 video subtitle translations and over 1,500 audio translations annually, with potential scaling options for increased demand.
