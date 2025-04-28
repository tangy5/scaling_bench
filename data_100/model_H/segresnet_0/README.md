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

Model Weight: <a href="https://www.dropbox.com/scl/fi/cryblbf85yp58gvph0j6r/model.pt?rlkey=w71r7d0k0h410yvvlxfqtzrii&st=magq6bda&dl=0"> link</a>. Put the model.pt file under model folder in segresnet_0

Raw training log file: <a href="https://www.dropbox.com/scl/fi/f0rmhrycmb2trhniomem9/training.log?rlkey=2vdkeqh6ud66lsabsw56wbpzb&st=9bnhbtzx&dl=0"> Log file link</a>.


segresnet_0/model/model.pt


## Inference

``` bash
bash run_testing.sh
```
