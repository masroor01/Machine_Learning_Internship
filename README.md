# Machine_Learning_Internship

# Decision Tree Implimentation for IRIS dataset

## Objectives

* Understand the logic behind decision trees.
* Visualize tree splits and interpret decisions.
* Apply the model to a classification dataset (Iris dataset).

## Project Structure

* `decision_tree_iris.ipynb`: The main Jupyter Notebook containing all the code for data loading, preprocessing, model training, evaluation, and visualization.
* `requirements.txt`: Lists all the Python libraries and their versions required to run the notebook.
* `.gitignore`: Specifies files and directories to be ignored by Git (e.g., virtual environment folder).

## Dataset

The project utilizes the famous [Iris dataset](https://www.kaggle.com/datasets/ucimldl/iris). This dataset contains 150 samples of iris flowers, each with four features (sepal length, sepal width, petal length, petal width) and a corresponding species (Setosa, Versicolor, Virginica).

## How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/YOUR_GITHUB_USERNAME/Decision-Tree-Implementation.git](https://github.com/YOUR_GITHUB_USERNAME/Decision-Tree-Implementation.git)
    cd Decision-Tree-Implementation
    ```
2.  **Create and Activate a Virtual Environment:**
    ```bash
    python -m venv .venv
    # On Windows:
    .venv\Scripts\activate
    # On macOS/Linux:
    source .venv/bin/activate
    ```
3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Open Jupyter Notebook:**
    You can open the `decision_tree_iris.ipynb` file directly in VS Code (ensure the Python extension and Jupyter extension are installed). Select the `.venv` kernel within the notebook.
5.  **Run Cells:** Execute each cell in the notebook sequentially to see the data exploration, model training, evaluation metrics, and tree visualization.

## Key Learnings & Observations

* **Decision Tree Logic:** Understood how decision trees make decisions by recursively splitting data based on feature values to maximize homogeneity within subsets.
* **Gini Impurity:** Learned about Gini impurity as a measure of node impurity, aiming to reduce it with each split.
* **Tree Visualization:** The `plot_tree` function proved invaluable for visualizing the decision path and interpreting the rules learned by the model.
* **Hyperparameter Tuning (max_depth):** Experimented with `max_depth` to control tree complexity and prevent overfitting, observing its effect on the tree structure and accuracy.
* **Model Evaluation:** Used accuracy, confusion matrix, and classification report to comprehensively evaluate the model's performance.

## Contributing

Feel free to fork this repository, make improvements, and submit pull requests.

## License

[Specify your license here, e.g., MIT License]
```

* Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username.
* Save the `README.md` file.
* Commit and push this change to GitHub as well.