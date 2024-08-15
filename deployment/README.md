## Deployment using Deepstream on Jetson Orin Nano 8Gb
In this part, a yolov8n model fine-tune on custom gun dataset is deployed on jetson orin nano 8gb using deepstream

## Requirement
1. Jetpack 6.0
2. Nvidia Deepstream SDK 7.0
   
## Running Instruction
clone the repo and go to the deployment folder
### Inference Using FP32
```bash
deepstream-app -c deepstream_app_config_fp32.txt
```
### Inference Using FP16
```bash
deepstream-app -c deepstream_app_config_fp16.txt
```
### Inference Using Int8
```bash
deepstream-app -c deepstream_app_config_int8.txt
```

## Output Results
1. [Result Using FP32](https://drive.google.com/file/d/1bsAMMSxn0w2el6t_XfEZp1AXGZbnnUoR/view?usp=sharing)
2. [Result Using FP16](https://drive.google.com/file/d/1C1K0HDz7Y4swUYoYiQrYIjc_GEuXtZxE/view?usp=sharing)
3. [Result Using Int8](https://drive.google.com/file/d/1ooP_5fLW8cK7e26vQEzVQf-H0g6ty_D6/view?usp=sharing)


