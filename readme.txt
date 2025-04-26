Description
Sign Language to Text is a real-time system that recognizes Indian Sign Language (ISL) gestures and translates them into readable text.
Built with Python, TensorFlow, Keras, and OpenCV, the project aims to bridge the communication gap between hearing-impaired and non-sign language users.

Features
Real-time ISL gesture recognition
Static and dynamic gesture detection
Text output interface
Lightweight and efficient model
Scalable for mobile/web deployment in the future

Tech Stack
Programming Language: Python
Libraries/Frameworks: TensorFlow, Keras, OpenCV, NumPy,LSTM
Tools: Jupyter Notebook / Visual Studio Code

Future Work
Add speech synthesis for sign-to-speech functionality.
Expand dataset to include more ISL gestures.
Deploy system to web and mobile platforms.
Multilingual translation (Hindi, English, etc.)


Clone the Repository
Open your terminal or command prompt and run:

git clone https://github.com/your-username/sign-language-to-text.git
cd sign-language-to-text

Set Up the Environment
It’s recommended to create a virtual environment:
python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows

Install Required Libraries
Install all dependencies listed in the requirements.txt file:
pip install -r requirements.txt

Download or Prepare the Model
Ensure the trained model file (trained_model.h5) is placed inside the model/ folder.
(Optional) You can train your own model using the dataset provided in the dataset/ folder.

Run the Application
Start the Python application:
python app.py

Use the Application
Allow your system to access the webcam if prompted.
Perform sign gestures in front of the camera.
The recognized gesture will appear as text on the screen.

(Optional) Train the Model
If you wish to retrain the model:
python train_model.py

Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

License
This project is open source and available under the MIT License.