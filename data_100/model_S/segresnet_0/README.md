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

Raw training log file: <a href="https://www.dropbox.com/scl/fi/b17eaf8g9hom3lgqs1452/training.log?rlkey=bgdak8j54lir51fb40q9pyee4&st=fuf7jue2&dl=0"> Log File</a>.

segresnet_0/test_data_sample/case_01/ct.nii.gz

Model Weight: <a href="https://www.dropbox.com/scl/fi/k6p5lys0hxxqe0bsic1zy/model.pt?rlkey=q6krkliatfjua2ucwfyp9fvgw&st=rjbpjaqz&dl=0"> link</a>. Put the model.pt file under model folder in segresnet_0

segresnet_0/model/model.pt


## Inference

``` bash
bash run_testing.sh
```
