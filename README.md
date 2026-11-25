# MindSignal -- Mental Wellness Prediction
MindSignal is a student wellness analytics frontend that collects
information about a user's daily routine, digital habits, lifestyle, and
perceived stress. It sends the submitted data to a FastAPI backend
and displays the mental wellness score returned by the prediction model.
Disclaimer: This project is for informational and educational
purposes only. Its prediction is not a medical diagnosis or a clinical
assessment.

# Features
- Responsive interface for desktop and mobile screens.
- Student profile and lifestyle input form.
- Digital-habit information, including screen time and daily phone
  unlocks.
- Perceived stress-level selector.
- Client-side input validation and field-level error messages.
- Loading, prediction-result, and error states.
- Animated score gauge displaying the predicted score out of 10.
- FastAPI integration using a JSON POST request.
- Built with plain HTML, CSS, and JavaScript on the frontend; no
  frontend framework or additional JavaScript library is required.
## Tech Stack

### Frontend
- **HTML5** – Structures the web application.
- **CSS3** – Handles styling, layout, and responsive design.
- **Vanilla JavaScript** – Manages form interactions and API communication.

### Backend
- **Python** – Core backend programming language.
- **FastAPI** – Provides the REST API for mental health score prediction.
- **Uvicorn** – ASGI server used to run the FastAPI application.

### Machine Learning
- **Trained Machine Learning Model** – Used to predict the mental health score.
- **Joblib** – Used to load the pre-trained model.
- **Pandas** – Used to prepare input data for model prediction.
- **Required Python Dependencies** – Libraries needed to load and run the trained model.
