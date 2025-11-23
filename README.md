# Student Introduction Analyzer 🎓

An AI-powered web application that evaluates student self-introductions based on communication rubrics. Built for the Nirmaan AI Intern Case Study.

## 🚀 Live Demo
**Live Application:** [(https://student-introduction-analyzer.onrender.com/)]  

## 📊 Sample Output
For the provided sample introduction:
- **Overall Score:** 91/100
- **Content Structure:** 35/40
- **Language & Grammar:** 20/20
- **Clarity:** 15/15
- **Engagement:** 15/15

## 🛠️ Features

- **Rubric-Based Scoring**: Implements exact scoring criteria from the provided Excel rubric
- **8 Assessment Criteria**: 
  - Salutation Level (0-5 points)
  - Keyword Presence (0-30 points)
  - Flow Structure (0-5 points)
  - Speech Rate (2-10 points)
  - Grammar (2-10 points)
  - Vocabulary Richness (2-10 points)
  - Clarity/Filler Words (3-15 points)
  - Engagement/Sentiment (3-15 points)
- **Real-time Analysis**: Instant feedback with detailed breakdown
- **Professional UI**: Clean, responsive web interface

## 🏗️ Technical Architecture

### Frontend
- **Flask** web framework
- **Bootstrap 5** for responsive UI
- **JavaScript** for dynamic interactions
- Progress bars and professional styling

### Backend
- **Python 3.8+** with Flask
- **Rule-based NLP** for grammar and keyword detection
- **Custom scoring algorithms** following exact rubric
- **No external API dependencies**

### Key Algorithms
- **Type-Token Ratio (TTR)** for vocabulary richness
- **Word-per-minute (WPM)** calculation for speech rate
- **Pattern matching** for grammar and keyword detection
- **Positive sentiment analysis** for engagement scoring




## 📁 Project Structure
```

student-introduction-analyzer/
│
├── app.py # Main Flask application
├── requirements.txt # Python dependencies
├── README.md # This file
├── deployment_guide.md # Detailed deployment instructions
│
└── templates/
    └── index.html # Web interface

```
## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- pip (Python package manager)

### Installation & Local Deployment

1. **Clone the repository**
```bash
  git clone https://github.com/amruthadevops/student-introduction-analyzer.git
  cd student-introduction-analyzer
```
2. **Install dependencies**

```bash
pip install -r requirements.txt
```
3. **Run the application**

```bash
python app.py
```
4. **Access the application**
```
Open your browser and navigate to: http://localhost:5000
```
## 📊 Assessment Criteria Details
| **Criteria**         | **Max Score** | **Scoring Method**                                |
| -------------------- | ------------: | ------------------------------------------------- |
| **Salutation Level** |             5 | Pattern matching for greeting quality             |
| **Keyword Presence** |            30 | Mandatory keywords (20) + Optional keywords (10)  |
| **Flow Structure**   |             5 | Order analysis (salutation → details → closing)   |
| **Speech Rate**      |            10 | Words-per-minute with ideal range **111–140 WPM** |
| **Grammar**          |            10 | Rule-based grammar error detection                |
| **Vocabulary**       |            10 | Type–Token Ratio (TTR) calculation                |
| **Clarity**          |            15 | Filler word rate analysis                         |
| **Engagement**       |            15 | Positive sentiment word density                   |


## 🔮 Future Enhancements
- Integration with language-tool-python for advanced grammar checking

- Audio file processing with speech-to-text

- Student performance tracking over time

- Teacher dashboard for classroom management

- Multi-language support

- Export reports in PDF format
## 🤝 Contributing


This project was developed as a case study for the Nirmaan AI Intern position. While it's a complete working solution, contributions and suggestions are welcome for educational purposes.

