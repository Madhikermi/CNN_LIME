# Classification and LIME Explanation of in-vivo Gastral Images
This repository provides code that explores the feasibility to add LIME explanations to a CNN's *labellings* as an alternative to train a neural network that learns based on *graphical annotations* and hence is interpretable *by design*.

## Dependencies

### Software
The dependencies are specified in the ``requirements.txt`` file.
Install the dependencies--ideally in a virtual environment--by running ``pip install -r requirements.txt``.

### Data
The code trains on the *Red Lesion Endoscopy Dataset* that is provided at https://rdm.inesctec.pt/dataset/nis-2018-003.
You need to download the data and adjust the path to your data according to your machine's setup.
Note that we train on *labels* and not on *graphical annotations*.


## Running the Code
To execute the code, first start the Jupyter notebook server by running ``jupyter notebook`` in the project's root directory.
Then, open the *CNN* notebook for training and the *LIME* notebook for explanation generation.
In both cases, you need to adjust the file to the data set you have downloaded.

**Note**: Although the model is provided in the repository, you need to run the data preparation step in the *CNN* notebook to be able to generate the explanations as specified in the *LIME* notebook.

