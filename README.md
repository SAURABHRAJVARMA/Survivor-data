Project Title: Analyzing Titanic First-Class Survivors: Fare and Age Distribution
Project Overview:
The project focuses on analyzing the demographic and financial aspects of passengers aboard the Titanic, particularly first-class survivors. The analysis is conducted using the famous Titanic dataset, with a specific focus on filtering passengers based on their survival status and ticket class. The primary goal is to explore and visualize the distributions of fares and ages among these first-class survivors.

Objectives:
Filter the Titanic dataset to include only passengers who traveled in first class and survived.
Extract and analyze key features such as Name, Pclass, Fare, Age, Ticket, Cabin, and Survived status.
Create visual representations of:
The fare distribution for first-class survivors.
The age distribution for first-class survivors.
Provide insights into the financial and age-related aspects of first-class survivors.
Dataset:
The dataset used for this project is the Titanic dataset (train.csv), which contains information about passengers, their demographics, class, fare, and survival status.

Key columns utilized in the project include:

Name: Passenger name.
Pclass: Ticket class (first-class passengers in this case).
Fare: The fare paid for the ticket.
Age: Age of the passengers.
Ticket: Ticket number.
Cabin: Cabin information.
Survived: Survival status (1 = survived, 0 = did not survive).
Methodology:
Data Loading and Filtering: The dataset is first loaded using Python's pandas library. Filtering is applied to retain only those passengers who were in first class (Pclass = 1) and survived (Survived = 1).

Data Selection: After filtering the data, the relevant columns (Name, Pclass, Fare, Age, Ticket, Cabin, and Survived) are selected for further analysis and visualization.

Visualization: Two primary visualizations are generated using the seaborn and matplotlib libraries:

Fare Distribution: A histogram with a KDE overlay, representing the spread of fares paid by first-class survivors.
Age Distribution: A histogram with a KDE overlay, showing the age distribution of first-class survivors.
These visualizations help in understanding the financial status (based on fare) and age demographics of the passengers who survived.

Results:
Fare Distribution:

The histogram of fare data provides insights into the variability of the fares paid by first-class survivors.
The KDE (Kernel Density Estimate) offers a smoother representation of the fare distribution, highlighting peaks in fare values.
Age Distribution:

The age distribution reveals the age range of first-class survivors, showing whether younger or older passengers had a higher survival rate.
The KDE helps to identify common age ranges among survivors.
Conclusion:
This project successfully filtered and visualized important aspects of first-class Titanic survivors. By focusing on the fare and age distributions, it provides an understanding of how economic and demographic factors may have influenced survival rates on the Titanic. Further analysis could explore other factors, such as family size or gender, and compare them across different ticket classes.

