# Project Development Phase

## Technologies Used

- Python 3.12
- Streamlit
- OpenAI Whisper
- Sentence Transformers
- ReportLab
- Librosa

## Modules Developed

### Speech Transcription Module
Converts uploaded audio into text using OpenAI Whisper.

### Semantic Analysis Module
Compares the student's spoken answer with the reference answer using Sentence Transformers to calculate semantic similarity.

### Concept Scoring Module
Calculates the concept understanding score based on semantic similarity and assigns grades.

### Feedback Generation Module
Provides personalized feedback according to the student's performance.

### PDF Report Generation
Generates a professional downloadable assessment report using ReportLab.

### Streamlit User Interface
Provides an easy-to-use interface for uploading audio files, viewing results, and downloading reports.

## Development Workflow

1. Audio Upload
2. Speech-to-Text Conversion
3. Semantic Similarity Analysis
4. Score Calculation
5. Grade & Feedback Generation
6. PDF Report Generation

## Folder Structure

- app/
- assets/
- data/
- reports/
- tests/
- README.md
- requirements.txt

## Development Outcome

A complete AI-powered educational application capable of evaluating students' conceptual understanding from spoken explanations automatically.
