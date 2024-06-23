# Course Recommendation System

## Overview
The Course Recommendation System is a machine learning-based web application designed to recommend similar courses from a dataset of over 3,000 courses from Coursera. The application preprocesses course data, applies text vectorization and cosine similarity measures, and provides course recommendations based on user input.

## Features
- Data preprocessing and cleaning
- Vectorization of course descriptions and skills
- Cosine similarity-based recommendation system
- Interactive web interface using Streamlit

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact) 

## Installation
To run the project locally, follow these steps:

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Ganesh2409/Course-Recommendation-System.git
    cd Course-Recommendation-System
    ```

2. **Create and activate a virtual environment (optional but recommended):**
    ```bash
    python -m venv env
    source env/bin/activate  # On Mac, use `env\Scripts\activate` # on windows 
    ```

3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Download the Coursera dataset and place it in the project directory.**

## Usage
1. **Run the preprocessing and model training script:**
    ```bash
    python coursera_course_recommendation_system_webapp.py
    ```

2. **Run the Streamlit application:**
    ```bash
    python -m streamlit run main.py
    ```

3. **Navigate to the provided local URL to use the web app.**

## Project Structure
```
courserecommendation/
├── Data/
│   └── Coursera.csv                                    # Coursera dataset (add this file)
├── models/
│   ├── course_list.pkl                                 # Precomputed similarity matrix
│   └── courses.pkl                                     # Processed course list
├── main.py                                             # Streamlit app script
├── coursera_course_recommendation_system_webapp.py     # Data preprocessing and model training script 
├── requirements.txt                                    # Python dependencies
└── README.md                                           # Project README file
```

## Contributing
We welcome contributions to enhance the Course Recommendation System. 

** Steps To contribute ** 

* Fork the repository.
* Create a new branch (`git checkout -b feature-branch`).
* Commit your changes (`git commit -am 'Add new feature'`).
* Push to the branch (`git push origin feature-branch`).
* Create a new Pull Request.


## Contact
For any questions or feedback, please contact:
- **Name** - [Ganesh Chowdhary P]()
- **Email** - [pinnamaneniganesh24@gmail.com ](mailto:your.pinnamaneniganesh24@gmail.com)
