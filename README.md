# Dog Breed Identification 

### Using Pre-trained Image Classifier

This project is part of my learning journey with Udacity's AI Programming with Python Nanodegree (AWS AI/ML Scholarship Course). The goal is to develop a Python application that utilizes pre-trained convolutional neural networks (CNNs) to classify dog breeds from input images. The project involves leveraging popular CNN models like ResNet, AlexNet, and VGG, extracting labels from image filenames, and analyzing classification results for accuracy assessment.

## Tech Stack

| Component        | Technology Stack                           |
|------------------|--------------------------------------------|
|  Languages       | Python, Shell                              |
|  CLI	           | Shell (Bash or equivalent)                 |
|  CNN Models      | ResNet, AlexNet, VGG                       |

## Project Components

| Python Files                 | Description                                                                                      |
|------------------------------|--------------------------------------------------------------------------------------------------|
| **get_input_args.py**        | Handles command-line arguments for specifying image directories, model architectures, and dog breed information. |
| **get_pet_labels.py**        | Extracts pet image labels from filenames to prepare for classification.                          |
| **classify_images.py**       | Utilizes CNN models to classify pet images and generate classification results.                   |
| **calculate_results_stats.py** | Computes statistics on classification results, including accuracy metrics for each model.         |
| **print_results.py**         | Displays a summary of classification results, highlighting correct and incorrect classifications of dog breeds. |
| **adjust_results4_isadog.py** | Adjusts classification results to identify whether images and classifications correspond to dogs. |
| **print_functions_for_lab_checks.py** | Includes print functions for validation and debugging during development.                        |

<br>
