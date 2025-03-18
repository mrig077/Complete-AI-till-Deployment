Installation & Running the API

Install dependencies:
pip install fastapi uvicorn torch opencv-python numpy

Run the API:
uvicorn main:app --reload

Test API via cURL or Postman
Send a POST request with a video file to:
http://localhost:8000/upload-video/
