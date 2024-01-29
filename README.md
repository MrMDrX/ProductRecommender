# Product Recommendation System

![Project Cover Image](https://www.devfi.com/wp-content/uploads/2022/04/Usecase-Recommender-Image.svg)

## Introduction

This repository contains the code for a Product Recommendation System. The system leverages various recommendation approaches, including rank-based recommendations, collaborative filtering, and model-based collaborative filtering using Singular Value Decomposition (SVD).

## Project Structure

- **ProductRecommender.ipynb**: The main Jupyter Notebook file containing the project code.
- **data/**: Directory containing the dataset file (you can download dataset from here [ratings_electronics.csv](https://www.kaggle.com/datasets/vibivij/amazon-electronics-rating-datasetrecommendation/download?datasetVersionNumber=1).
- **requirements.txt**: File specifying the Python dependencies for the project.
- **Presentation - Product Recommendation System.pdf**: Presentation about the project

## Dataset

I have used an amazon dataset on user ratings for electronic products, this dataset doesn't have any headers. To avoid biases, each product and user is assigned a unique identifier instead of using their name or any other potentially biased information.

- You can find the [dataset](https://www.kaggle.com/datasets/vibivij/amazon-electronics-rating-datasetrecommendation/download?datasetVersionNumber=1) here - https://www.kaggle.com/datasets/vibivij/amazon-electronics-rating-datasetrecommendation/download?datasetVersionNumber=1

- You can find many other similar datasets here - https://jmcauley.ucsd.edu/data/amazon/

## Instructions for Running the Notebook

1. Clone this repository to your local machine.

   ```bash
   git clone https://github.com/MrMDrX/ProductRecommender.git
   ```

2. Navigate to the project directory.

   ```bash
   cd ProductRecommender
   ```

3. Install the required dependencies.

   ```bash
   pip install -r requirements.txt
   ```

4. Open and run the `ProductRecommender.ipynb` notebook in Jupyter.

## Code Usage

- The notebook is organized into sections covering data exploration, preprocessing, and three recommendation approaches.
- Explore each section to understand the implementation details of the rank-based recommendation, user-based collaborative filtering, and model-based collaborative filtering using SVD.

## Dependencies

- Python 3.7+
- Libraries: pandas, numpy, scikit-learn, matplotlib

## Results

The project successfully generates product recommendations based on user preferences. Key findings and results are documented within the notebook.

## Next Steps

- Explore additional datasets for a more comprehensive evaluation.
- Implement a web API for deploying the recommendation system.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
