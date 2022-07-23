# Single-Image-Super-Resolution-using-ESRGAN
Using an already existing ESRGAN model, degrading our HR images to generate training data for finetuning and further checking the MSE and PSNR for the generated and the original HR images. Link to the original link of Real ESRGAN Repo - https://github.com/xinntao/Real-ESRGAN

Divide the complete dataset into train and test. 
Running the first cell of the Fine Tune code file generates a Real-ESRGAN file containing the different folders necessary. In the generated folder create a dataset -- DF2K--DF2K_HR and add the train HR images.
Now run the second cell which will apply a degradation model and generate LR images corresponding to HR.
Running the third cell would create a Meta file which would contain file names and would be of .txt format.
Now run the cells which would give links for the pre-trained models download those and add that to the RealESRGAN--experiments--pre-trained models and add all here.
After this step now goes to the RealESRGAN--options--FinetuneRealESRGAN and apply changes to it and save that.
Now run the cell with finetuning realesrgan--resume which will apply to our dataset.
Make an upload folder where add the Degraded Images generated from the Image_Degradation_Model and add there.
Run the inferences cell and the results would get stored in a results folder inside the RealESRGAN folder.
Complete Reference: https://github.com/xinntao/Real-ESRGAN/blob/master/docs/Training.md#Finetune-Real-ESRGAN-on-your-own-dataset
