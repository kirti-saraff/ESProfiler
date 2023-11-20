# ESProfiler

# Task Overview


## Tools and Technology Used

Programming Language: Python
Libraries: json, matplotlib
Environment: Google Colab(Jupyter Notebook) 
Version Control: Git and GitHub

This repository contains Python code for parsing and analyzing Mitre ATT&CK data, specifically focusing on adversaries, techniques, and their relationships. The goal is to transform the data into a more organized format and generate visualizations to understand the popularity of different techniques among adversaries.

## Instructions

### 1. Loading Mitre ATT&CK Data
The initial step involves loading the Mitre ATT&CK Stix data from the provided JSON file (enterprise-attack-14.0.json).
### 2. Filtering Relevant Information
Filter out only the relevant information related to adversaries and techniques, creating a dictionary to store adversaries by ID.
### 3. Organizing Data
Organize the data to have a single array containing technique objects, and a sub-array in each technique object containing the adversaries who use the technique. The resulting data was then saved into a new JSON file (reorganized_data.json).
### 4. Creating a Bar Chart
Generate a bar chart showing the popularity of each technique based on the number of adversaries using it.
Generate a bar chart specifically for the top techniques, including the technique names on the bars.
### 5. Repository Forking and Submission
The solution was then uploaded to a forked repository on Gitlab, following the provided instructions. The URL of the forked repository was emailed to the specified recipients.

## Conclusion

This analysis provides insights into the popularity of different techniques among adversaries, aiding in understanding potential security threats. The visualizations allow non-technical users to grasp the main threats effectively.

## Challenges Faced

Data Understanding: Understanding the complex structure of Mitre ATT&CK data and extracting relevant information posed a challenge.

Visualization Configuration: Configuring the bar charts to display technique names and IDs appropriately required careful consideration.

Adversaries List Extraction: Getting the right advasary list from the complex structure.

## Easiest Parts

Data Loading and Transformation:
Loading and transforming the Mitre ATT&CK data into a usable format was relatively straightforward. The Python programming language and the json library provided efficient tools for handling JSON data.

Bar Chart Creation:
Generating bar charts using Matplotlib proved to be a well-established and straightforward process. The library's documentation and flexibility facilitated the creation of visualizations to represent the popularity of techniques.



## Potential Improvements and Further Steps

Enhanced Data Filtering:
Implement more robust data filtering techniques to exclude irrelevant information further. This could involve refining the criteria for selecting adversaries and techniques.

Interactive Visualizations:
Explore the use of interactive visualization libraries such as Plotly. This could enhance the user experience and provide more dynamic insights into the data.

Automated Data Updates:
Develop a solution for automatically fetching the latest Mitre ATT&CK data from the source repository. This would ensure that the analysis is always based on the most up-to-date information.

Documentation:
Enhance code comments and documentation to provide clearer guidance on the code structure, data processing steps, and visualization configurations.

### Note:
This code was completed on google colab.

