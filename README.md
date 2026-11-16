# Face Recognition Using PCA (Eigenfaces)

## Live Application

The application is deployed on Netlify:

[Open Face Recognition Application](https://eclectic-chaja-88c78c.netlify.app)

## Project Overview

This project demonstrates face recognition using Principal Component Analysis (PCA), also known as the Eigenfaces approach.

The application provides an interactive explanation of the project, its Python implementation, mathematical concepts, and experimental results.

## Objectives

- Understand Principal Component Analysis.
- Learn how Eigenfaces are extracted from face images.
- Understand dimensionality reduction.
- Explore face matching using Euclidean distance.
- Visualize the mathematical concepts and project results.

## Dataset

The project uses the Olivetti Faces dataset.

- Total images: 400
- Number of individuals: 40
- Image dimensions: 64 × 64 pixels
- Features per image: 4096

## Methodology

1. Load the Olivetti Faces dataset.
2. Convert face images into feature vectors.
3. Divide the dataset into training and testing sets.
4. Apply PCA to extract 100 principal components.
5. Project face images into the reduced-dimensional space.
6. Calculate Euclidean distances to identify the closest matching face.
7. Evaluate the recognition results.

## Experimental Results

- Training images: 300
- Testing images: 100
- Principal components: 100
- Variance retained: 94.40%
- Recognition accuracy: 94.00%

## Technologies Used

- Python
- NumPy
- Matplotlib
- Scikit-learn
- HTML
- CSS
- JavaScript

## Repository Structure

```text
Face-Recognition-Using-PCA/
│
├── index.html
├── README.md
├── student-info.md
└── .gitignore
```

## How to View the Application

Open `index.html` in a web browser to view the local website.

You can also access the deployed application using the Netlify link above.

## Conclusion

This project demonstrates how PCA reduces the dimensionality of face images while retaining important information for face recognition. The Eigenfaces approach provides a practical application of linear algebra, eigenvectors, eigenvalues, and dimensionality reduction.