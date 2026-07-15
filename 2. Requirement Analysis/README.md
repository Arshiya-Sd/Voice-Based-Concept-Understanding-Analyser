# Requirement Analysis

## Functional Requirements

- Upload audio files in WAV, MP3, or M4A format.
- Convert speech into text using OpenAI Whisper.
- Load the reference answer for comparison.
- Calculate semantic similarity using Sentence Transformers.
- Generate a concept understanding score.
- Provide automatic grading and personalized feedback.
- Generate a downloadable PDF report.
- Display results through a Streamlit web interface.

## Non-Functional Requirements

- Fast processing of uploaded audio.
- Accurate speech recognition.
- User-friendly interface.
- High reliability and maintainability.
- Modular and scalable architecture.
- Secure handling of uploaded files.

## Software Requirements

- Python 3.12
- Streamlit
- OpenAI Whisper
- Sentence Transformers
- ReportLab
- Librosa

## Hardware Requirements

- Windows/Linux/macOS
- Minimum 4 GB RAM
- Internet connection (for installing dependencies)
- Microphone or recorded audio files

## User Requirements

- Students should be able to upload spoken answers.
- Teachers should receive an automated evaluation report.
- Users should be able to download assessment reports.

## Constraints

- Audio quality affects transcription accuracy.
- English language support in the current version.
- Semantic evaluation depends on the quality of the reference answer.
