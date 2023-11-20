# ESProfiler
This repository contains Python code for parsing and analyzing Mitre ATT&CK data, specifically focusing on adversaries, techniques, and their relationships. The goal is to transform the data into a more organized format and generate visualizations to understand the popularity of different techniques among adversaries.

## Instructions

### 1. Loading Mitre ATT&CK Data
The initial step involves loading the Mitre ATT&CK Stix data from the provided JSON file (enterprise-attack-14.0.json).
### 2. Filtering Relevant Information
Filter out only the relevant information related to adversaries and techniques, creating a dictionary to store adversaries by ID.
### 3. Organizing Data
Organize the data to have a single array containing technique objects, and a sub-array in each technique object containing the adversaries who use the technique.
### 4. Creating a Bar Chart
Generate a bar chart showing the popularity of each technique based on the number of adversaries using it.
Generate a bar chart specifically for the top techniques, including the technique names on the bars.

## Conclusion

This analysis provides insights into the popularity of different techniques among adversaries, aiding in understanding potential security threats. The visualizations allow non-technical users to grasp the main threats effectively.

### Note:
This code was completed on google colab.

