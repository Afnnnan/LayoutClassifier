# LayoutClassifier
This is a project developed as part of the DS203 course. It focuses on analyzing and classifying building layout designs using data science and machine learning techniques.

## Project Objectives

1. **Grouping Designs into Families:** Explore methods to group designs based on their shapes into distinct families. Test multiple approaches and present results from at least two methods.

2. **Classifying Layout Complexity:** Analyze layouts to classify complexity into Low, Medium, or High categories. Establish criteria for complexity classification based on formal analysis of the layouts.

3. **Speeding up Layout Design Process:** Develop a system to retrieve relevant prior layouts based on given parameters such as dimensions (length, width) of the tight-fitting box, layout area, and permissible complexity. Predict design family/families closest to specified parameters for efficient layout retrieval.

4. **Exploring Further Possibilities:** Solicit suggestions for additional tasks leveraging image data and mined information. Generate ideas for innovative applications or analyses beyond the specified tasks.

## Project Overview

The project involves the following key steps:

1. **Data Loading and Exploration:** Load the dataset of 1183 design layouts and conduct preliminary exploratory data analysis (EDA) to gain insights into its characteristics.

2. **Feature Engineering:** Generate shape-related features using OpenCV, including perimeter^2/area ratio, sum of distances from centroid, total corners, hull to contour area ratio, box to contour area ratio, layout area, and dimensions of the tight-fitting box.

3. **Dimensionality Reduction:** Utilize techniques such as t-Distributed Stochastic Neighbor Embedding (t-SNE) to reduce the dataset's dimensionality while preserving essential relationships.

4. **Clustering:** Apply clustering algorithms (e.g., K-Means, hierarchical clustering) to group layouts into distinct families based on shared characteristics.

5. **Complexity Classification:** Classify layouts into Low, Medium, or High complexity categories based on the perimeter^2/area ratio.

6. **Layout Retrieval:** Develop a system to retrieve similar layouts based on specified parameters such as dimensions and complexity level.

7. **Cost Estimation:** Assign feature weights to layout attributes in terms of dollars to predict estimated costs associated with each layout.

8. **Further Analysis:** Explore additional possibilities for leveraging image data and mined information to enhance design processes and productivity.

## Repository Structure

- `data/`: Contains datasets and resources used in the project.
- `scripts/`: Includes Python scripts for different project tasks such as data preprocessing, analysis, and modeling.
- `results/`: Stores the results and outputs generated during the project.
