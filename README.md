# AI-Powered Resume Analyzer

![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![License](https://img.shields.io/badge/license-MIT-green)

## Project Overview
AI-Powered Resume Analyzer is an intelligent system that uses Natural Language Processing (NLP) and Machine Learning to automatically evaluate resumes, extract key information, and provide actionable hiring insights. The system can parse resumes in multiple formats, analyze skills, experience, and qualifications, and match candidates to job requirements.

## Tech Stack
- **Backend**: Python, Flask/FastAPI
- **NLP Libraries**: spaCy, NLTK, transformers
- **ML Framework**: scikit-learn, TensorFlow
- **Database**: PostgreSQL, MongoDB
- **Frontend**: React.js, Material-UI
- **APIs**: OpenAI GPT, PDF parsing libraries
- **Testing**: pytest, unittest

## Features
- ✅ Multi-format resume parsing (PDF, DOCX, TXT)
- ✅ Automatic skill extraction and categorization
- ✅ Experience timeline analysis
- ✅ Education verification and scoring
- ✅ Job description matching with similarity scores
- ✅ Keyword optimization suggestions
- ✅ ATS compatibility checking
- ✅ Candidate ranking and shortlisting
- ✅ Export reports in PDF/Excel
- ✅ RESTful API for integration

## Setup Instructions

### Prerequisites
- Python 3.8 or higher
- Node.js 14+ (for frontend)
- PostgreSQL/MongoDB

### Installation

```bash
# Clone the repository
git clone https://github.com/shithel9360/ai-powered-resume-analyzer.git
cd ai-powered-resume-analyzer

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Download NLP models
python -m spacy download en_core_web_sm

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run database migrations
python manage.py migrate

# Start the backend server
python app.py

# In a new terminal, start the frontend
cd frontend
npm install
npm start
```

### Running Tests

```bash
# Run all tests
pytest tests/

# Run with coverage
pytest --cov=app tests/
```

## Demo

![Demo GIF Placeholder](https://via.placeholder.com/800x400.png?text=Demo+GIF+Coming+Soon)

## API Documentation

API endpoints available at `/api/docs` when server is running.

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

## License

MIT License - see LICENSE file for details

## Contact

Shithel - [@shithel9360](https://github.com/shithel9360)
