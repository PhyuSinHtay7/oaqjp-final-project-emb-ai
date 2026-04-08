# Final Project: Emotion Detection Application

## Overview
This project is a web-based application that detects emotions from user input text using the Watson NLP API. It identifies five emotions: anger, disgust, fear, joy, and sadness, and determines the dominant emotion.

## Features
- Detects emotions from text input  
- Returns emotion scores and dominant emotion  
- Handles empty or invalid input  
- Flask web interface  
- Unit testing included  
- PyLint score: 10/10  

## Technologies Used
- Python  
- Flask  
- Requests  
- Watson NLP API  

## Project Structure
```
final_project/
│── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
│── templates/
│   └── index.html
│── server.py
│── test_emotion_detection.py
│── README.md
```

## Installation & Setup
1. Clone the repository:
```
git clone https://github.com/PhyuSinHtay7/oaqjp-final-project-emb-ai.git
cd oaqjp-final-project-emb-ai
```

2. Install dependencies:
```
pip install flask requests
```

3. Run the application:
```
python3 server.py
```

4. Open in browser:
```
http://localhost:5000
```

## Example
Input:
```
I am happy
```

Output:
```
The dominant emotion is joy.
```

## Error Handling
For empty input:
```
Invalid text! Please try again!
```

## Testing
```
python3 test_emotion_detection.py
pylint server.py
```

## API Endpoint
```
/emotionDetector?textToAnalyze=your_text_here
```

## License
Apache 2.0