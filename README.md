### This repository should be placed inside finn/notebooks/ directory

### 1. Set up the environement.yml
### 2. Get the dataset through the link in the datasets/ folder
### 3. Run the jupyter notebook which walk through the process of building the VGG10 model for 27 modulations
### 3.1 You can either train the model from scratch or get the models from the 27ml_rf folder. 
### 4. The model under the format [name]_tidy.onnx is desired for running the next step, indicating that it's preprocessing input node has been removed. This is expected for the next step, which is generating the driver to be run on FPGA
