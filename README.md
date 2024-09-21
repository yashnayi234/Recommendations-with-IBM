# Recommendations-with-IBM

This repository contains a project focused on building a recommendation system using IBM Watson data. The project was developed as part of a data science course, and it showcases various techniques to recommend articles to users based on their interactions.

## Project Overview

In this project, we aim to create a recommendation system using the data provided by IBM, which tracks user interactions with articles on a platform. The project explores different recommendation techniques, including:
- Rank-based recommendations
- Collaborative filtering
- Matrix factorization

### Dataset

The dataset includes two primary files:
- **User-Article Interactions**: Contains user interactions with articles.
- **Articles Metadata**: Contains information about articles available on the platform.

### Project Structure

- `Recommendations_with_IBM.ipynb`: The main Jupyter Notebook containing the code for the project. This notebook walks through the following:
  - **Exploratory Data Analysis (EDA)**: Provides insights into the dataset, including the number of users, articles, and interactions.
  - **Rank-Based Recommendations**: Recommends articles based on popularity.
  - **User-User Collaborative Filtering**: Recommends articles by identifying similar users based on their interactions.
  - **Matrix Factorization**: Implements a recommendation engine using SVD (Singular Value Decomposition).
  - **Evaluation**: Measures the performance of the recommendation algorithms.

### Key Files

- `Recommendations_with_IBM.ipynb`: The main notebook for this project.
- `data/user-item-interactions.csv`: User-item interaction data.
- `data/articles_community.csv`: Article metadata.

### Prerequisites

Before running the notebook, ensure you have the following Python packages installed:

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `seaborn`
- `surprise` (for matrix factorization)

You can install the required packages using the following command:

```bash
pip install -r requirements.txt
```

### Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yashnayi234/Recommendations-with-IBM.git
   ```
   
2. Navigate to the directory:
   ```bash
   cd Recommendations-with-IBM
   ```

3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Recommendations_with_IBM.ipynb
   ```

4. Follow the notebook instructions to explore the recommendation system.

### Results

The recommendation system built in this project provides:
- A rank-based recommendation system.
- Collaborative filtering using user similarities.
- A matrix factorization-based recommendation system using Singular Value Decomposition (SVD).
- Evaluation of the system using precision, recall, and accuracy metrics.

### Contributing

Feel free to fork this repository and submit a pull request if you'd like to contribute. For major changes, please open an issue first to discuss the proposed changes.

### License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
