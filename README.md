# Project Name: Adapting To Shape 

## Project Objective
Source Code for the data analysis and modeling for our published paper: Mu, Y., Schubö, A. & Tünnermann, J. Adapting attentional control settings in a shape-changing environment. Atten Percept Psychophys 86, 404–421 (2024). https://doi.org/10.3758/s13414-023-02818-x

## Tech Stack
- **Data Cleaning**: Pandas, NumPy
- **Analysis & Modeling**: arviz, acvsfit, pymc
- **Visualization**: Matplotlib
- **Database**: csv

## Data Source
[ChoiceAnalysis/data/]

## Key Analysis Steps
1. **Data Cleaning**: Handle missing values and outlier Response Times and accuracies.
2. **Visualization**:
   - The choice (0-100%) of one target over one experimental cycle (99 trials)

## Core Findings
In rich visual environments, humans have to adjust their attentional control settings in various ways, depending on the task. Especially if the environment changes dynamically, it remains unclear how observers adapt to these changes. In two experiments (online and lab-based versions of the same task), we investigated how observers adapt their target choices while searching for color singletons among shape distractor contexts that changed over trials. The two equally colored targets had shapes that differed from each other and matched a varying number of distractors. Participants were free to select either target. The results show that participants adjusted target choices to the shape ratio of distractors: even though the task could be finished by focusing on color only, participants showed a tendency to choose targets matching with fewer distractors in shape. The time course of this adaptation showed that the regularities in the changing environment were taken into account. A Bayesian modeling approach was used to provide a fine-grained picture of how observers adapted their behavior to the changing shape ratio with three parameters: the strength of adaptation, its delay relative to the objective distractor shape ratio, and a general bias toward specific shapes. Overall, our findings highlight that systematic changes in shape, even when it is not a target-defining feature, influence how searchers adjust their attentional control settings. Furthermore, our comparison between lab-based and online assessments with this paradigm suggests that shape is a good choice as a feature dimension in adaptive choice online experiments.

## How to Run
See this supplementary document of our paper: https://static-content.springer.com/esm/art%3A10.3758%2Fs13414-023-02818-x/MediaObjects/13414_2023_2818_MOESM1_ESM.pdf
