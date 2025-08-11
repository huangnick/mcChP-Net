# mcChP-Net
A neural network model that segments choroid plexus using T1+FLAIR images. 

# Introduction
The choroid plexus (ChP) is a structure in the brain that secretes cerebro-spinal fluid (CSF). It constitutes a blood-CSF barrier that protect the central nervous system (CNS) from peripheral toxic substances. It also plays a major role monitoring CNS immune responses. The degeneration of ChP is related to various neurological disorders. The increase of ChP volume has been found in multiple diseases, suggesting its utility as a disease marker.

# Model details
The training data set included 51 participants, pseudorandomly selected from both ADNI and our local small vessel disease database. To enhance the generalizability ofour segmentation method, we used MRl sequences obtainedfrom various scanner vendors (GE, Siemens, Philips, UIH). The testing data set included participants from ADNl, scanned using 3 scanner vendors (GE, Siemens, Philips). Our model showed superior accuracy (mean DICE = 0.875) in the testing dataset. A sample image can be seen below.

<img width="1001" height="934" alt="image" src="https://github.com/user-attachments/assets/3f7fd1db-5ef3-47d0-9f9d-808823dc8faa" />

# Usage
The mcChP-Net can be easily used in the nnU-Net environment. Please check https://github.com/MIC-DKFZ/nnUNet for detailed instructions. The trained model can be downloaded from (uploading...). 
The T1 and FLIAR images of the same subject should be coregistered first. The first input modality is FLAIR, and the second is T1.
