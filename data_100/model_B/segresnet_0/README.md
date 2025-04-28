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

Raw training log file: <a href="https://www.dropbox.com/scl/fi/9z15lnpy1xaej7cr43pgq/training.log?rlkey=cq3jy3dsahapyh18xfiq8n201&st=tf3rlalt&dl=0"> Log file link</a>.

Model Weight: <a href="https://www.dropbox.com/scl/fi/tktmud7v46e8picosokar/model.pt?rlkey=kshfjangc86nnan1ie2mbvuhx&st=r8s1m7vd&dl=0"> link</a>. Put the model.pt file under model folder in segresnet_0

segresnet_0/model/model.pt


## Inference

``` bash
bash run_testing.sh
```
