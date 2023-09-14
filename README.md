# Post-Earthquake-Building-Assessement
# Building Safety Assessment Questionnaire App

This is a Python web application for conducting a building safety assessment questionnaire after an earthquake. Users can answer a series of questions and based on their responses, the app will categorize the building as Red (Rouge), Yellow (Jaune), or Green (Vert) according to the level of damage. The app uses Flask as the web framework and reads data from a CSV file.

## Installation

1. Make sure you have Python installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2. Clone or download this repository to your local machine.

3. Navigate to the project directory using the command line.

4. Install the required Python packages by running the following command:

   ```bash
   pip install flask
   ```

## Usage

1. Ensure you have the `database.csv` file containing the assessment questions and choices in the same directory as the application.

2. Start the Flask web server by running the following command:

   ```bash
   python app.py
   ```

3. Open a web browser and go to `http://localhost:5000/` to access the assessment questionnaire.

4. Click the "Start a New Assessment" button to begin a new assessment.

5. Answer each question by selecting one of the available choices (non, a, b, c) and clicking the "Submit" button.

6. After answering all questions, the app will display the assessment result.

## CSV Data Format

Ensure that the `database.csv` file follows the following format:

- The CSV file should contain two columns: "Category" and "Description".
- Each row represents a question with its description.
- The choices for each question should be represented as follows:
  - "non" for no or minimal damage.
  - "a" for damage to a few isolated elements (up to 10%).
  - "b" for damage to many elements (from 10% to 50%).
  - "c" for damage to most elements (over 50%).
- The CSV file should not contain a header row.

## License

This project is licensed under the MIT License.

## Acknowledgments

- This app was created as a tool for post-earthquake building assessment.
- Special thanks to the Flask community for providing an excellent web framework.

Feel free to contribute to or modify this project as needed. Enjoy using the Building Safety Assessment Questionnaire App!
