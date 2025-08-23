# FashionMNIST-Clustering 🖼️✨

Welcome to the **FashionMNIST-Clustering** project! This repository
implements unsupervised learning to cluster Fashion-MNIST images using
**K-Means** and **Agglomerative Clustering**. Explore the code to
visualize clusters and evaluate clustering performance! 🚀

## 📖 Overview

This project applies clustering algorithms to the [Fashion-MNIST
dataset](https://github.com/zalandoresearch/fashion-mnist), which
contains 70,000 grayscale images of 10 fashion categories (e.g.,
T-shirt, Trouser, Sneaker). The code: - Loads and preprocesses the
dataset 📂 - Performs K-Means and Agglomerative Clustering 🧠 -
Visualizes cluster centroids and sample images 📊 - Evaluates clustering
with metrics like ARI and V-measure 📈

## 🛠️ Features

-   **Dataset**: Loads Fashion-MNIST with error handling for
    connectivity issues.
-   **Preprocessing**: Standardizes data using `StandardScaler`.
-   **Clustering**:
    -   K-Means with 10 clusters, `k-means++` initialization.
    -   Agglomerative Clustering with Ward linkage (500 samples).
-   **Visualization**: Displays cluster centroids and up to 5 sample
    images per cluster.
-   **Evaluation**: Computes Adjusted Rand Index (ARI) and V-measure for
    both algorithms.

## 📋 Requirements

To run the code, install the required Python packages:

``` bash
pip install numpy matplotlib scikit-learn
```

## 🚀 Usage

1.  Clone the repository:

    ``` bash
    git clone https://github.com/shahin-ro/FashionMNIST-Clustering.git
    ```

2.  Navigate to the project directory:

    ``` bash
    cd FashionMNIST-Clustering
    ```

3.  Run the script:

    ``` bash
    python fashionmnist_clustering.py
    ```

The script will: - Load and preprocess 5,000 samples from
Fashion-MNIST. - Perform K-Means and Agglomerative Clustering. - Display
cluster visualizations and print evaluation metrics.

## 📈 Results

-   **K-Means**: Visualizes 10 cluster centroids as 28x28 grayscale
    images and shows sample images per cluster.
-   **Agglomerative Clustering**: Processes 500 samples, visualizes
    clusters, and evaluates performance.
-   **Metrics**: Outputs ARI and V-measure to assess clustering quality.

## 📁 File Structure

-   `fashionmnist_clustering.py`: Main Python script with clustering and
    visualization code.
-   `README.md`: Project documentation (you're reading it!).

## 🌟 Contributing

Contributions are welcome! 🙌 Feel free to: - Open issues for bugs or
suggestions 🐛 - Submit pull requests with improvements or new features
💡

## 📜 License

This project is licensed under the MIT License. See the
[LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

-   [Fashion-MNIST
    dataset](https://github.com/zalandoresearch/fashion-mnist) by
    Zalando Research.
-   [scikit-learn](https://scikit-learn.org/) for clustering and
    evaluation tools.
-   Built with ❤️ using Python and matplotlib.

Happy clustering! 🎉
