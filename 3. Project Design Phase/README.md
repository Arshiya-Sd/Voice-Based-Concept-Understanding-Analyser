# Project Design Phase

## System Architecture

The Voice-Based Concept Understanding Analyzer follows a modular architecture. Each module performs a specific task, making the system easy to maintain, test, and extend.

### Modules

1. **Speech Transcription Module**
   - Converts uploaded audio into text using OpenAI Whisper.

2. **Semantic Analysis Module**
   - Compares the student's answer with the reference answer using Sentence Transformers.

3. **Concept Scoring Module**
   - Calculates the semantic similarity score and assigns grades.

4. **Report Generation Module**
   - Generates a professional PDF report containing score, grade, and feedback.

5. **User Interface**
   - Built using Streamlit for an interactive user experience.

## Workflow

Audio Upload
↓
Speech-to-Text (Whisper)
↓
Reference Answer Loading
↓
Semantic Similarity Analysis
↓
Concept Score Calculation
↓
Grade & Feedback Generation
↓
PDF Report Generation

## Design Goals

- Modular architecture
- Easy maintenance
- High accuracy
- Scalable design
- User-friendly interface
