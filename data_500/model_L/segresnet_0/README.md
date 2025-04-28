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

Model Weight: <a href="https://www.dropbox.com/scl/fi/kqp4imp5eww195ti7oz83/model.pt?rlkey=ge4nle2pzieppstb09hzfyhcp&st=699krdjr&dl=0"> link</a>. Put the model.pt file under model folder in segresnet_0

Raw training log file: <a href="https://www.dropbox.com/scl/fi/00gr41jqdwh6clobgzeo8/training.log?rlkey=pvnpvfm4aqsh91m6dqkpdsi1q&st=iu64230n&dl=0"> Log file link</a>.


segresnet_0/model/model.pt


## Inference

``` bash
bash run_testing.sh
```
