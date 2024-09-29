# PraShikshan

Welcome to **PraShikshan**, an automated interview system developed as part of a college assignment. This project aims to streamline the interview process for job seekers and recruiters. The system conducts interviews by asking predefined questions, recording responses, and analyzing them to generate insightful feedback using sentiment analysis.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Future Improvements](#future-improvements)
- [Contributors](#contributors)

## Project Overview

**PraShikshan** automates the process of conducting interviews. It asks questions, records answers using WebRTC for video/audio, and uses **Sentence-BERT (SBERT)** for sentiment and content analysis. The system helps recruiters save time by providing summaries and recommendations based on the interview performance.

### Key Objectives:
- Automate interviews with minimal human intervention.
- Provide structured feedback using sentiment analysis.
- Make the recruitment process more efficient.

## Features

- **Predefined Question Bank:** Includes a range of technical, behavioral, and situational questions.
- **WebRTC-based Recording:** Captures candidates' responses via video or audio.
- **SBERT Sentiment Analysis:** Analyzes the tone and sentiment of the responses.
- **Interview Summary Report:** Generates a summary with a candidate's overall performance and recommendations.

## Technologies Used

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js
- **Database:** SQLite
- **Real-time Communication:** WebRTC
- **Sentiment Analysis:** Sentence-BERT (SBERT)

## Installation

### Prerequisites:

- [Node.js](https://nodejs.org/)
- [Python 3.x](https://www.python.org/downloads/) (for SBERT)
- [SQLite](https://www.sqlite.org/index.html)

### Steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/PraShikshan.git
   cd PraShikshan
   ```

2. Set up the backend:
   - Install Node.js dependencies:
     ```bash
     npm install
     ```

3. Set up a virtual environment for SBERT (optional but recommended):
   ```bash
   python3 -m venv env
   source env/bin/activate  # For Windows: env\Scripts\activate
   ```

4. Install Python dependencies for SBERT:
   ```bash
   pip install -r requirements.txt
   ```

5. Run the application:
   ```bash
   node app.js
   ```

6. Open your browser and navigate to `http://localhost:3000`.

## Usage

- Recruiters can log in, upload a list of candidates, and initiate interviews.
- Candidates can log in and proceed with their scheduled interview through video/audio prompts.
- Results, including sentiment analysis, are available for recruiters to view after the interview.

## Future Improvements

- **Live Interview Mode:** Allow for live interviews with real-time sentiment analysis.
- **Expanded Question Bank:** Add more technical and domain-specific questions.
- **Integration with Other Platforms:** Export interview results to HR or recruitment platforms.

## Contributors

- **[@ayushsharma1603](https://github.com/ayushsharma1603)**
- **[@Dani8608](https://github.com/Dani8608)**
