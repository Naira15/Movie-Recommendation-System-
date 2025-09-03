# Movie Recommendation System

This project implements a movie recommendation system using **collaborative filtering**, a technique that makes recommendations based on the behavior and preferences of other users. The system analyzes user-movie ratings to identify patterns and suggest movies that a user is likely to enjoy.

---

### 🌟 **Key Features**

* **User-Based Collaborative Filtering**: Recommends movies by finding users with similar tastes and suggesting movies they rated highly.
* **Item-Based Collaborative Filtering**: Recommends movies by finding movies similar to those a user has already liked.
* **Performance Evaluation**: The system's effectiveness is measured using **Precision@K**, a metric that evaluates the relevance of the top `k` recommendations.
* **Jupyter Notebook Interface**: The entire project is contained within a single Jupyter Notebook (`Movie Recommendation System.ipynb`), making it easy to follow the data processing, model building, and evaluation steps.

---

### 📂 **Dataset**

The system uses the **MovieLens 100K Dataset**, a classic dataset for building and testing recommendation systems. The dataset is composed of two main files:
* `u.data`: Contains 100,000 ratings from 943 users on 1,682 movies. Each entry includes a user ID, movie ID, rating, and timestamp.
* `u.item`: Provides detailed information about the 1,682 movies, including their title, release date, and genre categories.

---

### 🚀 **How to Run the Project**

To run this project, you will need to have Python and Jupyter Notebook installed.

1.  **Clone the Repository**: Download the project files to your local machine.
2.  **Install Dependencies**: Make sure you have the necessary libraries installed. You can do this by running the following command in your terminal:
    ```bash
    pip install pandas numpy scikit-learn
    ```
3.  **Download the Dataset**: Download the MovieLens 100K dataset and place the `u.data` and `u.item` files in the same directory as the notebook.
4.  **Launch Jupyter Notebook**: Open the notebook and run the cells in sequence. The notebook will guide you through the process of building the recommendation system.
    ```bash
    jupyter notebook "Movie Recommendation System .ipynb"
    ```

---

### 📊 **Evaluation Results**

The project compares the performance of the user-based and item-based collaborative filtering approaches. The results are summarized in a table within the notebook, showing their respective **Mean Precision@5** and **Mean Precision@10** scores.

* **User-based CF**:
    * Mean Precision@5: 0.19
    * Mean Precision@10: 0.21
* **Item-based CF**:
    * Mean Precision@5: 0.26
    * Mean Precision@10: 0.28