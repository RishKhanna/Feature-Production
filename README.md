# Explanatory Variables for High Energy Physics (HEP) Cuts

## Introduction:
This project aims to optimize the selection of variables for better cuts in High Energy Physics (HEP) analysis, particularly in the context of particle physics experiments. By employing genetic algorithms and statistical measures, the project identifies a set of explainable variables that can enhance the discrimination between signal and background processes.

## Dependencies:
```
- torch
- random
- copy
- scipy
- math
- matplotlib
- pandas
- numpy
- tqdm
```
## Code Overview:
The project is structured into several components:

1. **Data Import and Preprocessing**:
   - Data from different physics processes (e.g., signal, background) is imported from CSV files and normalized for further analysis.

2. **Calculation of Cross Sections**:
   - The cross sections for various physics processes are calculated based on theoretical values and branching ratios.

3. **Fitness Function**:
   - A fitness function is defined to evaluate the performance of different combinations of variables. The function utilizes a chi-square statistic comparing the observed and expected event distributions.

4. **Genetic Algorithm**:
   - A genetic algorithm is employed to optimize the selection of variables. It operates over multiple generations, with individuals representing different combinations of variables.

5. **Visualization**:
   - The project includes visualization functions to display histograms comparing signal and background distributions for selected variables.

## Usage:
1. **Data Preparation**:
   - Ensure that the required data files are available in the specified CSV format.
   - Make any necessary adjustments to the data import and preprocessing steps based on specific requirements.

2. **Execution**:
   - Run the provided Python script, ensuring that all dependencies are installed.
   - Adjust parameters such as population size, vector length, and number of generations as needed for the optimization process.

3. **Interpretation**:
   - Analyze the output to identify the best combination of variables obtained from the genetic algorithm.
   - Utilize visualization functions to gain insights into the discriminatory power of selected variables.

## Conclusion:
The project facilitates the identification of explainable variables that can enhance the efficiency and effectiveness of cuts in High Energy Physics analyses. By employing a combination of genetic algorithms and statistical measures, it offers a systematic approach to optimizing variable selection for improved discrimination between signal and background processes.
