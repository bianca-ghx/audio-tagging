# Audio Tagging

This project was developed for the Description and Retrieval of Audiovisual Content course at the Universitat Politècnica de Catalunya. The input data was taken from the [Kaggle Freesound General-Purpose Audio Tagging Challenge](https://www.kaggle.com/c/freesound-audio-tagging). The purpose of this project is to implement an audio tagging system consisting of a SVM classifier using MFCC features. Furthermore, PCA was used for dimensionality reduction.

## Installation
To install and run this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/bianca-ghx/audio-tagging.git
    ```
2. Navigate to the project directory:
    ```sh
    cd audio-tagging
    ```

## Usage
To use the audio tagging system, follow these instructions:

1. Ensure the audio data is in the correct format.
2. Run the Jupyter Notebook provided in the repository:
    ```sh
    jupyter notebook notebooks/code.ipynb
    ```
3. Follow the steps in the notebook to preprocess the data, extract features, apply dimensionality reduction, and train the SVM classifier.
4. Evaluate the model using the provided test data.
   
## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements
This project was developed as part of the Description and Retrieval of Audiovisual Content course at the Universitat Politècnica de Catalunya. Special thanks to the Kaggle community for providing the dataset used in this project.
