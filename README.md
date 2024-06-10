## Disaster Tweet Classification with LSTMs

This repository contains the code for a Long Short-Term Memory (LSTM) based classifier that identifies disaster-related tweets. 

### Project Overview

This project tackles the task of classifying tweets as either indicating a disaster event or being a normal tweet. An LSTM model is implemented and evaluated, demonstrating the effectiveness of this architecture for capturing long-term dependencies within textual data. Hyperparameter tuning is also performed to optimize the model's performance.

### Getting Started

This project requires Python libraries like TensorFlow and Keras. 

1. Clone this repository:
   ```bash
   git clone https://github.com/<your_username>/disaster_tweet_classification.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```

### Running the Notebook

The core implementation is within the `disaster_tweet_classification.ipynb` notebook. Open it in a Jupyter notebook environment and follow the instructions within the notebook for data loading, model training, and evaluation.

### Model Architecture

The `model` section defines the LSTM architecture used for classification. You can explore and modify this script to experiment with different hyperparameters or network structures.


### Results

The final accuracy achieved by the model is displayed within the `disaster_tweet_classification.ipynb` notebook. The notebook also highlights how LSTMs performed better than simpler architectures for this task.

### Future Scope

While this project establishes a solid foundation, there's room for further exploration:

* **Data Augmentation:** Techniques like back-translation or synonym replacement can be leveraged to increase training data size and diversity.
* **Ensemble Learning:** Combining predictions from multiple models (LSTMs with CNNs) holds potential for improved performance.
* **Real-Time Implementation:** Building a system to continuously monitor tweets and identify potential disasters in real-time can  facilitate faster response times.
* **Fine-tuning for Specific Disasters:** Training separate models for different disaster types (earthquakes, floods) could potentially increase accuracy in specific scenarios.

By delving into these possibilities, we can develop even more robust tweet classification models to enhance disaster relief efforts.
