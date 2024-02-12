# Goldstandard for Interlinking User Stories with GUI Prototypes

This dataset represents the goldstandard that we created to evaluate the LLM-based prompting models to interlink user stories with GUI prototypes and to foster further research. In particular, the goldstanard supports *(1)* the evaluation of models for the binary classification of whether a user story is contained in a respespective GUI protoype, *(2)* the evaluation of models matching the GUI components fulfilling a user story and *(3)* the creation of preliminary results for recommending potentially relevant GUI feature implementations for a given user story. The gold standard is based on the large-scale GUI dataset Rico and contains 210 examples in the test set and 21 examples in the train set and has the following structure:

- **rico_id**: The rico id of the GUI taken from the Rico GUI dataset
- **user_story**: The user story for this GUI
- **comp_ids**: The GUI component IDs fulfillin the user story. For each of the GUIs encompassed in our dataset, we provide additional JSON datasets including the GUI components with the respective identifiers and GUI component groups in the *rico_annotations* directory
- (**label**: The binary label used in our evaluation)
