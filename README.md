# Amazon Review Sentiment Analysis

This project implements a sentiment analysis model using a Recurrent Neural Network (RNN) to predict sentiments from Amazon reviews. The dataset is scraped from Amazon product reviews, and the model classifies the reviews as positive, negative, or neutral based on their content.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Sujit-S-2908/Sentiment-Analysis---Amazon-reviews.git

2. Ensure you have Python installed on your system. You can download it from python.org.
3. Install the required packages using pip

## Data Collection

The dataset is collected using web scraping techniques from Amazon product reviews. The reviews are stored in a CSV file, which includes relevant columns such as:

- reviewerName
- overall (rating)
- reviewText
- reviewTime
- day_diff
- helpful_yes
- helpful_no
- total_vote
- score_pos_neg_diff
- score_average_rating
- wilson_lower_bound

## Model Architecture

The RNN model is implemented using TensorFlow/Keras. The architecture consists of:

- An embedding layer to transform words into vectors.
- One or more LSTM layers to capture sequential dependencies in the review text.
- A dense output layer with a softmax activation function to classify sentiments.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing
Feel free to submit issues or pull requests for improvements or features you'd like to add!
