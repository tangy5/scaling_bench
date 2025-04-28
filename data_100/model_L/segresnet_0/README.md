# Scaling bench run

Note: 

First, please cd to the segresnet_0 folder

then, open the run_testing.sh script to modify dataset root

follow the command to run inference

# Installing Dependencies
Dependencies can be installed using:
``` bash
pip install monai==1.3.0
```

# Models

Example testing data: <a href="https://drive.google.com/file/d/168Nr1ULMoVXrTORVsq-BouuVUDmXRMll/view?usp=sharing"> link</a>. Put the testing data folder under the segresnet_0 folder. 

segresnet_0/test_data_sample/case_01/ct.nii.gz

Model Weight: <a href="https://www.dropbox.com/scl/fi/3a71ridj9e8q5jb3cqafv/model.pt?rlkey=ek7nlvsqcep4zz5odjr6xe0g4&st=pqsj9i1j&dl=0"> link</a>. Put the model.pt file under model folder in segresnet_0


Raw training log file: <a href="https://www.dropbox.com/scl/fi/zdxp7dpsu2pol90566rk6/training.log?rlkey=5h7jfkgi507qrqieu5z71lmqg&st=1da24qcc&dl=0"> Log file link</a>.


segresnet_0/model/model.pt


## Inference

``` bash
bash run_testing.sh
```
