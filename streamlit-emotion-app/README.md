# Streamlit Emotion Prediction App

This project is a Streamlit application that predicts the emotion of a given text input using pre-trained machine learning models. The application utilizes Natural Language Processing (NLP) techniques to clean and process the input text before making predictions.

## Project Structure

```
streamlit-emotion-app
├── app.py                # Main application file
├── requirements.txt      # List of dependencies
└── README.md             # Project documentation
```

## Installation

To run this application, you need to have Python installed on your machine. Follow these steps to set up the project:

1. Clone the repository or download the project files.
2. Navigate to the project directory:
   ```
   cd streamlit-emotion-app
   ```
3. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Running the Application

To start the Streamlit application, run the following command in your terminal:
```
streamlit run app.py
```

This will open a new tab in your web browser with the application interface.

## Usage

- Enter a comment in the text input box.
- Click the submit button to predict the emotion of the comment.
- The predicted emotion will be displayed on the screen.

## Dependencies

The application requires the following Python packages:

- streamlit
- pandas
- numpy
- scikit-learn
- nltk
- seaborn
- matplotlib

Make sure to install these packages using the `requirements.txt` file provided.

## License

This project is open-source and available under the MIT License.