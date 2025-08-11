# mcChP-Net
A neural network model that segments choroid plexus using T1+FLAIR images. The training data set included 44 participants, pseudorandomly selected from both ADNI and our local small vessel disease database. To enhance the generalizability ofour segmentation method, we used MRl sequences obtainedfrom various scanner vendors (GE, Siemens, Philips, UIH). The testing data set included participants from ADNl, scanned using 3 scanner vendors (GE, Siemens, Philips). 
Our model showed superior accuracy (mean dice = 0.878mean precision = 0.872,mean recall = 0.888) compared with 2 previously used methods, FreeSurfer(mean dice = 0.387, mean precision =0.487, mean recall = 0.342) and the T1-based Gaussian mixture models (mean dice = 0.529, mean precision =0.570, mean recall = 0.S20). A sample image can be seen below.

<img width="1001" height="934" alt="image" src="https://github.com/user-attachments/assets/3f7fd1db-5ef3-47d0-9f9d-808823dc8faa" />

# Usage
The mcChP-Net can be easily used in the nnU-Net environment. Please check https://github.com/MIC-DKFZ/nnUNet for detailed instructions. The trained model can be downloaded from (uploading...). 
