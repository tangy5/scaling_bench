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

Model Weight: <a href="https://www.dropbox.com/scl/fi/l0ueyeh24lxig5vi1eogz/model.pt?rlkey=65vzhxhbi9r1ao7hsgywyhdd4&st=wc8g32r8&dl=0"> link</a>. Put the model.pt file under model folder in segresnet_0

Raw training log file: <a href="https://www.dropbox.com/scl/fi/h8rxsys7f61q6nqqfuc0w/training.log?rlkey=xhzczx9ygiebi2f2jv8nxwql0&st=15o94x1q&dl=0"> Log file link</a>.


segresnet_0/model/model.pt


## Inference

``` bash
bash run_testing.sh
```
