# Client analysis

### Introduction
This project aims to analyze user data and logs to gain insights into customer behavior and preferences. The dataset includes information about clients, their premium status, age, and logs of their activities including success rate, platform used, and time.

### Setup
To run this project, you will need Python installed along with the pandas and seaborn libraries.

```bash
pip install pandas seaborn
```

### Tasks were given:
1. Check the size of the tables, variable types, presence of missing values, and descriptive statistics.
2. Determine the client who made the most successful operations (success == True).
3. Identify the platform with the highest number of successful operations.
4. Determine which platform premium clients prefer.
5. Visualize the distribution of client ages based on their premium status.
6. Plot the distribution of the number of successful operations.
7. Visualize the number of successful operations made on the computer platform based on age, using sns.countplot (x – age, y – number of successful operations). Determine the age group with the highest number of successful actions.

### Data Description
**user_data:**
- client – user identifier
- premium – whether the client is premium
- age – age

**logs:**
- client – user identifier
- success – result (success – 1, failure – 0)
- platform – platform
- time – time in Unix format

### Conclusion
This project provides insights into customer behavior and preferences based on the analysis of user data and logs. It helps identify trends, such as preferred platforms, successful actions, and age demographics, which can be valuable for business decision-making and marketing strategies.
