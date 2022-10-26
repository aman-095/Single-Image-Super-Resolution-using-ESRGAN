
# Single-Image-Super-Resolution-using-ESRGAN

Using an already existing ESRGAN model, degrading our HR images to generate training data for finetuning and further checking the MSE and PSNR for the generated and the original HR images. Link to the original link of Real ESRGAN [Repository](https://github.com/xinntao/Real-ESRGAN)


## Methods Required

- **Image Degradation**

- **Finetuning and Parameter Optimization Techniques** 

- **Image data visualization Techniques** 

- **Evaluation Metrics** 







## Roadmap

1. [Fine-tuned Real-ESRGAN model](https://drive.google.com/drive/folders/1hfQsSBfyg2jjiDDVdLqksCy8dO8acOP5?usp=sharing)
This is the main file with all the datasets and the fine-tuned models.

- Installing libraries and dependency
- Cloning the [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN) repository on the Jupyter notebook
- [Dataset](https://www.kaggle.com/datasets/ambarish/breakhis) Division into Train, Validation and Test
- Running the first cell of the Fine Tune code file generates a Real-ESRGAN file containing the different folders necessary. In the generated folder create a dataset -- DF2K--DF2K_HR and add the train HR images.
- Run the second cell which will apply a degradation model and generate LR images corresponding to HR.
- Running the third cell would create a Meta file which would contain file names and would be of .txt format.
- Now run the cells which would give links for the pre-trained models download those and add that to the RealESRGAN--experiments--pre-trained models and add all here.
- After this step now go to the RealESRGAN--options--FinetuneRealESRGAN and apply changes to it and save that.
- Now run the cell with finetuning realesrgan--resume which will apply to our dataset.
- Make an upload folder where add the [Degraded Images](https://drive.google.com/drive/folders/1--1YF1CJJwScm8NJs4agrXsyvPLz1cVp?usp=sharing) generated from the [Image_Degradation_Model](https://github.com/aman-095/Single-Image-Super-Resolution-using-ESRGAN/blob/main/Image_Degradation_Model.ipynb) and add there.
- Run the inferences cell and the [results](https://drive.google.com/drive/folders/1hfQsSBfyg2jjiDDVdLqksCy8dO8acOP5?usp=sharing) would get stored in a results folder inside the RealESRGAN folder.

2. All the essential links for the original and the generated datasets[Links](https://github.com/aman-095/Single-Image-Super-Resolution-using-ESRGAN/blob/main/Links.txt)
This contains all the qualitative analysis of the results and detailed data visualization.


## Fine-tuned Images
![Fine-tuned](https://i.postimg.cc/KvCVDc1J/SRGAN.png)

![Fine-tuned](https://i.postimg.cc/BQZD72Kv/3-out.png)

## Results

[Results](https://github.com/aman-095/Single-Image-Super-Resolution-using-ESRGAN/blob/main/ESRGAN_Results.pdf)

Contains the LR, HR and Fine-tuned Images with evaluation scores i.e MSE and PSNR values.


## Feedback

If you have any feedback, please reach out to us at bhansali.1@iitj.ac.in


## 🔗 Links
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://aman-095.github.io/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/aman-bhansali-b4aa26228/)

