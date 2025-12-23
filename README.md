# mcChP-Net
A neural network model that segments choroid plexus using T1+FLAIR images. 

# Introduction
The choroid plexus (ChP) is a structure in the brain that secretes cerebro-spinal fluid (CSF). It constitutes a blood-CSF barrier that protect the central nervous system (CNS) from peripheral toxic substances. It also plays a major role monitoring CNS immune responses. The degeneration of ChP is related to various neurological disorders. The increase of ChP volume has been found in multiple diseases, suggesting its utility as a disease marker.

# Model details
The training data set included 51 participants, pseudorandomly selected from both ADNI and our local small vessel disease database. To enhance the generalizability of our segmentation method, we used MRl sequences obtained from various scanner vendors (GE, Siemens, Philips, UIH). The testing data set included participants from ADNl, scanned using 3 scanner vendors (GE, Siemens, Philips). Our model showed excellent accuracy (mean DICE = 0.878) in the testing dataset. A sample image can be seen below.
<img width="814" height="425" alt="image" src="https://github.com/user-attachments/assets/0ddcfb66-e548-4dab-834f-f757d4811120" />


# Usage
The mcChP-Net can be easily used in the nnU-Net environment. Please check https://github.com/MIC-DKFZ/nnUNet for detailed instructions. The trained model can be downloaded from (https://1drv.ms/f/c/36bb922ed9e9f74e/IgAxTOKUFiQPT6OQ4muGVJOrAQ8bLvjU3vauuLpT0P1_5cg?e=Ev2WtF). 
The T1 and FLIAR images of the same subject should be coregistered first. The first input modality is FLAIR, and the second is T1.
Email: huangpy@zju.edu.cn

# Method reference
Lin M, Zeng Q, Zhong S, Nie S, Zhang R, Hong H, Liu L, Wang S, Li K, Luo X, Chen Y. Association between choroid plexus morphological alterations, Alzheimer pathologies, and cognitive impairment: a longitudinal study. Neurology. 2025 Dec 23;105(12):e213953.
