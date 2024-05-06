# Lung-Disease-ML-Diagnosis

**Description:**  
A machine learning project aimed at aiding early diagnosis of lung diseases using anonymized medical image datasets. This project reduces the diagnostic workload for physicians through accurate disease classification.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Dataset Information](#dataset-information)
- [DINOv2 Model Information](#dinov2-model-information)
- [Running on Kaggle](#running-on-kaggle)
- [Development](#development)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. **Clone the Repository:**

   Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/Lung-Disease-ML-Diagnosis.git
   ```
   
2. **Python Virtual Environment Setup**:Create a virtual environment using Python 3.12.0:
    ```bash
    python3.12 -m venv venv
    ```

3. **Activate the Virtual Environment**
    - On Windows:
        ```bash
        venv\Scripts\activate
        ```
    - On macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
        
4. **Install Dependencies**:Install the necessary packages using the **'requirements.txt'** file:
        ```bash
        pip install -r requirements.txt
        ```

## Usage

1. Ensure that the virtual environment is activated.
2. Run the desired script to analyze and classify lung disease images using DINOv2 models.

## Dataset Information

[Dataset Link](https://www.kaggle.com/datasets/vikrantrajput/lungs-disease-data?resource=download)

**About Dataset**  
Artificial Intelligence has evolved a lot and is currently able to solve problems that are very complex and require human specialization. One such area is healthcare.

A lot of research happens every day to use deep learning for the betterment of humanity, and one such is healthcare.


## DINOv2 Model Information

DINOv2, developed by Meta AI, is an advanced deep learning model designed for self-supervised learning. This project uses DINOv2 models to perform efficient image analysis and classification for the anonymized lung disease datasets.

To learn more about DINOv2 models, you can refer to Meta AI's official documentation [here](https://ai.meta.com/dinov2).

## Running on Kaggle

For GPU acceleration and more computational power, you can execute the project on Kaggle:

1. **Download the Repository:**  
   Upload the project files or clone the repository to your Kaggle notebook environment.

2. **Setup Environment:**  
   Create and activate a Python virtual environment:
   ```bash
   !python -m venv venv
   !source venv/bin/activate
   ```
3. **Install Dependencies:**  
   Install the required libraries:
   ```bash
   !pip install -r requirements.txt
   ```
4. **Run Analysis:**  
   Execute the provided analysis scripts to analyze the anonymized medical image datasets.

## Development

For development purposes, ensure that your environment is set up according to the instructions provided above. Always create new branches for feature additions or bug fixes, and submit pull requests with clear and concise descriptions of your changes.

## Contributing

Contributions to this project are welcome! Please open an issue or submit a pull request if you'd like to suggest improvements, add features, or fix bugs.

## License

This project is licensed under the [MIT License](LICENSE).
