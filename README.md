# Interlinking User Stories and GUI Prototyping: A Semi-Automatic LLM-based Approach

The supplementary material of our submission to the RE 2024 conference is structured as follows:

- **datasets**: This directory contains the collected user story and GUI annotation dataset across multiple preprocessing steps
- **goldstandard**: This directory contains the final goldstandard of user story and GUI annotations that has been used to produce the evaluation results shown in the paper
- **materials**: This directory contains additional materials including the exclusion criteria and other materials
- **notebooks**: This directory contains the jupyter notebooks containing *(1)* the code for preprocessing the datasets, *(2)* the code for the experiments of the discussed LLM-based prompting models and the respective evaluations results and *(3)* the code for the error analysis showing multiple example prediction errors
- **prompting**: This directory contains all the employed prompts for the three different tasks investigated in the paper including *(1)* prompts for classifying whether a user story is implemented in a GUI protoype, *(2)* prompts for matching GUI components to user stories and *(3)* prompts for generating implementation recommendations for a given user story