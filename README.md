# ML-Based Predictive Modeling for Ketoprofen Adsorbance Using Composite Material of Magnetic Nanoparticles and Metal Organic Frameworks (MMOF).

## Overview

Welcome to the repository for my project on predicting the adsorbance of ketoprofen drug molecules from wastewater using a composite material of magnetic nanoparticles (Fe3O4) and metal organic frameworks (MMOF). This project aims to develop an accurate predictive model using machine learning techniques.

## Project Highlights

- **Introduction and Objectives:** The project focuses on synthesizing Fe3O4 nanoparticles and creating MMOF to develop an effective adsorbent for ketoprofen. The primary goal is to predict the adsorption of ketoprofen molecules using the composite material.

- **Data Collection and Preparation:** Categorized samples include Fe3O4 nanoparticles, conventional MOF (Basolite), and MMOF, with absorption measurements taken at different time intervals. The dataset contains variables such as 'serial_no,' 'sample,' 'wavelength,' 'concentration_in_ppm,' 'adsorbance,' and 'duration_in_hours.'

- **Exploratory Data Analysis (EDA):** Thorough data analysis revealed patterns and correlations. Techniques were employed to handle missing values and unsaturated readings, ensuring data quality.

- **Feature Engineering Techniques:** Data preprocessing, including outlier handling using the IQR method, was performed. 'Sample' variable encoding used one-hot encoding.

- **Modeling Approach:** Three algorithms - Linear Regression, Gradient Boosting Regressor, and MLP Regressor - were utilized to build the predictive model. Hyperparameter tuning was performed to optimize model performance.

- **Results:** The MLP Regressor emerged as the most promising model, achieving an R-squared value of 0.974. It excelled in capturing non-linear relationships and generalizing to unseen data.

- **Business Impact:** The developed model enhances process efficiency, reduces costs, improves products and services, ensures compliance, and supports sustainability and environmental stewardship.

## Requirements

For the execution of this project, we utilized the following tools and libraries:

- Python, serving as our programming language for data analysis and coding.
- Libraries like pandas, scikit-learn, Matplotlib, and Seaborn for essential data manipulation, machine learning, and visualization tasks.
- Colab Notebook as our development environment for running code, analyzing data, and generating visualizations.

- ## Code and Notebooks
Access the [Colab notebook](MMOF_Adsorbance_Prediction_Ketoprofen.ipynb) to view the detailed project implementation.


## Acknowledgements
- Inspiration from similar projects and online tutorials from AlmaBetter.
- I would like to express my gratitude to Aniket Parab, for their guidance and support throughout this project.

## Contact Information
For any questions or feedback, feel free to contact me at [Mail](mailto:rahulshinde8605746446@gmail.com). and [Linkedin](https://www.linkedin.com/in/rahul-shinde5/).

## License
This project is shared under the [MIT License](LICENSE).

## Conclusion

In conclusion, this project successfully developed a predictive model for ketoprofen adsorbance using a composite material of magnetic nanoparticles and metal organic frameworks. The chosen MLP Regressor demonstrated high accuracy, capturing complex relationships and performing well on unseen data.

## Future Work

There are several avenues for future work. Further optimization of the model's hyperparameters and exploring additional features could potentially enhance its performance. Additionally, conducting experiments to validate the model's predictions in real-world scenarios would be a valuable step forward.

## Project Status

The project is currently in its completed state. The developed model and insights can be utilized for various applications related to drug removal from wastewater.



