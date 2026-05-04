Emotion Detection AI Web Application

This project is an AI-based Emotion Detection system developed using Python and Gradio. It takes user input in the form of text and predicts the emotion behind the sentence using a pretrained Natural Language Processing model.

The system classifies emotions such as joy, sadness, anger, fear, love, surprise, disgust, and neutral. It also shows the confidence level of prediction in percentage format along with a visual representation using a bar chart.

The application includes a simple authentication system with signup and login functionality. After login, the user is redirected to a dashboard where they can enter text, view emotion predictions, analyze results, see graphical visualization, track history, and export data into an Excel file.

Technologies Used:
Python
Gradio for web interface
Pandas for data handling
Matplotlib for visualization
Transformers for AI emotion detection
Openpyxl for Excel export

Installation:
To run this project, install the required dependencies using the following command:

!pip install gradio pandas matplotlib transformers openpyxl -q

Features:
User Signup and Login system
Secure login session flow
AI-based emotion detection from text input
Multiple emotion classification (joy, sadness, anger, fear, love, etc.)
Emotion display with confidence score
Emoji representation of detected emotion
Bar chart visualization of emotion probabilities
History tracking of user inputs
Export results to Excel file
Logout functionality
Clean and simple user interface using Gradio

How it Works:
User signs up or logs in
User enters a sentence in the input box
Pretrained AI model analyzes the text
Emotion and confidence score are displayed
Graphical bar chart is generated for emotion distribution
Data is stored in history and can be downloaded as Excel file

This project demonstrates the use of Machine Learning and Natural Language Processing to build an interactive AI web application using Gradio.
