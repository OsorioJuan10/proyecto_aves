# Project Name
This project is a part of the  **Proyecto 1 de Innovación Tecnológica** course in the Applied Artificial Intelligence Master, Universidad Icesi, Cali Colombia. 

#### -- Project Status: [Active]

## Contributing Members


## Contributing Members

**Team Leader:** [Juan Camilo Osorio Colonia](https://github.com/OsorioJuan10) ([@OsorioJuan10](https://github.com/OsorioJuan10))


## Contact
* Feel free to contact the team leader or the instructor with any questions or if you are interested in contributing!


## Project Intro/Objective
The purpose of this project is to develop machine learning models to automatically identify bird species from audio recordings using passive acoustic monitoring in Colombia’s Magdalena Medio region. Students will extract audio features and compare classification algorithms, including Support Vector Machines and ensemble methods, while addressing class imbalance and the challenges of real-world recordings. The project has the potential to support biodiversity monitoring and conservation efforts by enabling more efficient, non-invasive species identification. It also promotes data-driven environmental research and strengthens the connection between machine learning education and local ecological challenges.

### Methods Used
* Inferential Statistics
* Machine Learning
* Data Visualization
* Predictive Modeling
* etc.

### Technologies
* R 
* Python
* D3
* PostGres, MySql
* Pandas, jupyter
* HTML
* JavaScript
* etc. 


## Project Description: Identifying Species by Their Calls in Colombia

Passive acoustic monitoring offers a non-invasive approach to studying biodiversity by collecting environmental audio recordings and identifying species through their vocalizations. This project builds on the BirdCLEF+ 2025 challenge, focused on the Middle Magdalena Valley in Colombia, a region of high ecological importance. The main objective is to develop machine learning models that can identify bird species from short audio recordings and evaluate their potential for supporting biodiversity monitoring and conservation.

### Data Sources and Research Questions

The project draws on audio recordings from Xeno-Canto and datasets associated with previous BirdCLEF competitions. The complete dataset contains approximately 28,564 recordings covering 206 species. To make the project manageable within the course, students will work with a subset of 10–20 species and short audio clips.

The analysis will explore the following research questions:

1. How accurately can machine learning models identify bird species from their vocalizations?
2. Which audio features provide the most useful information for distinguishing between species?
3. How does class imbalance affect classification performance, particularly for species with fewer recordings?
4. How robust are the models to background noise and differences between training recordings and real-world field recordings?

The main hypothesis is that audio features extracted from recordings contain sufficient discriminatory information to classify species with reasonable accuracy. However, performance is expected to vary across species, particularly when recordings are limited, vocalizations are similar, or background noise is substantial.

### Data Analysis and Modeling Approach

The project will follow a structured machine learning workflow:

- **Exploratory Data Analysis (EDA):** Examine the distribution of recordings across species, identify class imbalance, inspect recording durations, and visualize audio signals and spectrograms.
- **Feature Extraction:** Compute Mel-frequency cepstral coefficients (MFCCs), spectral statistics, and other relevant acoustic features to represent the recordings numerically.
- **Classification Models:** Train and compare Support Vector Machines (SVMs) and ensemble methods, such as Random Forests, using consistent evaluation procedures.
- **Model Evaluation:** Use stratified train-test splits or cross-validation where appropriate and compare accuracy, macro-F1 score, precision, recall, and confusion matrices to assess performance across species.
- **Optional Unsupervised Learning:** Explore clustering to investigate whether recordings from the same species exhibit similar acoustic patterns without using species labels during clustering.
- **Visualization and Interpretation:** Present class distributions, spectrograms, confusion matrices, and comparative model-performance plots to identify strengths, weaknesses, and potential sources of misclassification.

### Challenges and Potential Impact

The main challenges include class imbalance, variable recording quality, background noise, differences in recording equipment and environments, and the risk of data leakage when recordings from the same source are distributed across training and test sets. Another important challenge is ensuring that models generalize beyond the recordings used for training.

The project connects practical machine learning techniques with a real conservation problem in Colombia, illustrating how automated acoustic analysis can help researchers monitor biodiversity more efficiently and potentially support ecological research and conservation decisions.

### References and Data Resources

- [BirdCLEF+ 2025 Competition and Dataset — Kaggle](https://www.kaggle.com/c/birdclef-2025)
- [BirdCLEF+ 2025 Task Description — ImageCLEF](https://www.imageclef.org/BirdCLEF2025)
- [BirdCLEF 2025 Overview and Results](https://www.researchgate.net/publication/396180283_Overview_of_BirdCLEF_2025_Multi-Taxonomic_Sound_Identification_in_the_Middle_Magdalena_Colombia)


