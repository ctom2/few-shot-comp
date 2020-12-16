# few-shot-comp
Submission for few-shot classification competition

The execution of the jupyter notebook is based on the tutorial notebook provided in the starting kit by the competition organizers (found here: [tutorial.ipynb](https://github.com/ebadrian/metadl/blob/master/starting_kit/tutorial.ipynb)). The basic requirement for executing is the metadl repository with all required librairies and dependencies (if the tutorial runs, the submission will run as well). 

The notebook is split into four main cells. The first one creates a copy if the transfer basline provided by the organizers. Next, the configuration file of the copied model is overwritten with the configuration for the submission. The third cell overwrites the code for the transfer model with the code for the submission model. Once the files are overwritten, the model can be executed the same way as shown in the tutorial. Only difference here is that the code directory has been changed so it links to the submission model (`../baselines/submission`). The model then proceeds with backbone training and subsequent evaluation. 
