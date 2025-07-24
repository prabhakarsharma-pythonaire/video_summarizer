# Video Summary Generator

A web application that generates summaries from YouTube videos and uploaded video files using AI.

## Features

- YouTube video summarization
- Video file upload and summarization
- Multiple summary formats (markdown, bullet points, narrative)
- Adjustable summary length (short, medium, long)
- Multi-language support
- Sentiment analysis
- Keyword extraction
- History tracking

## Tech Stack

- **Backend**: FastAPI (Python)
- **Frontend**: Streamlit (Python)
- **AI**: Google Gemini API
- **Video Processing**: MoviePy, SpeechRecognition
- **YouTube**: pytube, youtube-transcript-api

## Setup

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up environment variables (see `.env.example`)
4. Run the backend: `python backend_logic.py`
5. Run the frontend: `streamlit run app.py`

## API Endpoints

- `POST /summarize/youtube` - Summarize YouTube videos
- `POST /summarize/upload` - Summarize uploaded videos
- `GET /summaries` - Get all summaries
- `GET /summaries/{id}` - Get specific summary
- `DELETE /summaries/{id}` - Delete summary
- `GET /download/{id}` - Download summary

## Environment Variables

Create a `.env` file with:


GOOGLE_API_KEY=your_google_api_key_here


```

## Step 3: Create a `.env.example` file

Create a `.env.example` file with:

```env
GOOGLE_API_KEY=your_google_api_key_here
```

## Step 4: Update your `requirements.txt`

Let me check your current requirements and suggest improvements: