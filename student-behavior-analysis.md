# Student Behavior Analysis in Education with K-Means Clustering

This project aims to explore and analyze a dataset comprising various features related to student behavior, including demographic information, academic details, engagement metrics, parental engagement, absence records, and class performance. The analysis includes exploratory data analysis (EDA) and k-means clustering to identify patterns, outliers, and the structure of the data, thereby providing insights into student behaviors and characteristics.

## Dataset Summary

The dataset consists of 480 entries with features categorized into numerical and categorical variables, with no missing values across all features.

### Numerical Features

- **Raised Hands**: The average times students raised their hands is approximately 46.78, with a wide range of participation levels indicated by a standard deviation of 30.78.
- **Visited Resources**: On average, students visited resources about 54.80 times, suggesting varying levels of engagement with the material provided.
- **Announcements View**: The average views are around 37.92, showing diverse attention to announcements.
- **Discussion**: The average number of discussions engaged in by students is 43.28, indicating different levels of class interaction.

### Categorical Variables Distribution

- **Gender**: Balanced distribution between male and female students.
- **Nationality**: Students come from a variety of nationalities, indicating a diverse student body.
- **Educational Stage**: Encompasses different educational stages, showing a broad age range.
- **Subject Topic**: Wide range of subjects with some having higher enrollments.
- **Parent School Satisfaction**: Predominantly good, with a significant proportion not satisfied.
- **Student Absence Days**: Captures both frequently absent students and those seldom absent, with a larger number in the latter category.

## Insights from Distribution Analysis

The distributions of both numerical and categorical variables provide a foundation for understanding student behaviors. Notably, active engagement metrics like raised hands, visited resources, announcements view, and participation in discussions are varied, suggesting potential criteria for segmentation.
<img src="Images/1.png" width="500" alt="Faculty-Wise Distribution of Feedback">
<img src="Images/1.png" width="500" alt="Faculty-Wise Distribution of Feedback">
<img src="Images/1.png" width="500" alt="Faculty-Wise Distribution of Feedback">
## Relationships and Correlations

Boxplots indicate a positive relationship between engagement metrics and academic performance or class level. Higher class level students tend to participate more actively, suggesting a link between student engagement and academic performance.

## K-Means Clustering Preparation

The next steps involve preparing the data for k-means clustering to identify patterns or clusters within the students based on their behaviors and characteristics. This will include selecting relevant features for clustering, normalizing the data, and determining the optimal number of clusters.

### Challenges in Analysis

The process of determining the optimal number of clusters using the elbow method and silhouette score faced computational limitations, leading to an interruption of the analysis. A more focused analysis with a reduced range of cluster values was attempted but also encountered issues.

### Proposed Next Steps

Under normal circumstances, the analysis would proceed with the elbow method and silhouette score to determine the optimal number of clusters, followed by performing k-means clustering and analyzing the characteristics of each cluster. This would involve examining the central tendencies of the features within each cluster and visualizing the clusters to provide actionable insights into different groups of students.

## Conclusion

Despite execution challenges, this project outlines a robust framework for understanding student behavior through k-means clustering. The insights gained from the exploratory data analysis set the stage for a deeper investigation into student engagement and academic performance, providing a foundation for tailored interventions or support strategies to enhance educational outcomes.
