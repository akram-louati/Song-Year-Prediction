Files:
- Preprocessing.IPYNB to generate the spectrograms and at the end saves the splitted data in .npy files
- train.IPYNB contains the code for training
- test.IPYNB contains the code for testing

You can train and test using the data saved in the .npy files that I generated. If you would like to regenerate the data, you should download the fma_small.zip from https://github.com/mdeff/fma. The directories containing the .mp3 files should be in ./fma_small/fma_small. regenerating the data might take some time. After running the Preprocessing.IPYNB, the .npy files containing the data will be saved in the working directory. You can use these files to train and test the model.