# Spam Email Detection with Flask

Welcome to the Spam Email Detection project! This Flask-based web application leverages machine learning models trained on spam and ham datasets to predict whether an input email text is spam or not. The project includes three algorithms: K-Nearest Neighbors (KNN), Linear Regression (LR), and Naive Bayes (NB).

## Features

- Predicts if an email text is spam or ham using three different algorithms.
- Web-based user interface for easy input and prediction.
- Models include KNN, Linear Regression, and Naive Bayes trained on both Count Vectorization and TF-IDF representations.

## Getting Started

Follow these instructions to set up and run the Spam Email Detection project on your local machine.

### Prerequisites

- Python 3.9 or higher
- Clone this repository:

  ```bash
  git clone https://github.com/Ajit-2111/email_filtering.git
  cd email_filtering
  ```

- Install required packages using:

  ```bash
  pip install -r requirements.txt
  ```

### Running the Application

1. Navigate to the project directory:

   ```bash
   cd email_filtering
   ```

2. Run the Flask application:

   ```bash
   python home.py
   ```

3. Open your web browser and go to [http://localhost:5000](http://localhost:5000).

4. Enter an email text in the input box, and the application will predict whether it's spam or not using the trained models.

## Models Used

The following models have been trained and included in the project:

- **KNN Count Vectorization Model**: `knn_count_model.joblib`
- **KNN TF-IDF Model**: `knn_tfidf_model.joblib`
- **Linear Regression Count Vectorization Model**: `lr_count_model.joblib`
- **Linear Regression TF-IDF Model**: `lr_tfidf_model.joblib`
- **Naive Bayes Count Vectorization Model**: `nb_count_model.joblib`
- **Naive Bayes TF-IDF Model**: `nb_tfidf_model.joblib`

## Project Structure

- **home.py**: Flask application script containing the main server logic.
- **templates**: HTML templates for rendering the web pages.
- **static**: Directory for static files such as CSS and JavaScript.
- **models**: Directory for storing the trained spam detection models.
- **requirements.txt**: List of Python packages required for the project.

## Contributing

Contributions are welcome! If you have ideas for improvements, bug reports, or new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Enjoy using the Spam Email Detection with Flask! If you have any questions or feedback, feel free to reach out.

Happy classifying! 📧🚫
