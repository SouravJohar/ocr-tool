# ocr-tool
A simple [OCR tool](https://fastapi-ocr-1.herokuapp.com) made using FastAPI and Tesseract.

## Watch the videos
- [OCR with Pytesseract](https://www.youtube.com/watch?v=L7nGuOCP8GI)
- [Building a web app using FastAPI](https://youtu.be/JC5q22g3yQM)
- [Deploying to Heroku](https://www.youtube.com/watch?v=Lghw-Uuk86Q)

## Setup
```
brew install tesseract
pip install -r requirements.txt
```

## Starting a local server
```
cd src
uvicorn server:app --reload
```
