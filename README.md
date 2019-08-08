# seg_sta_nois

Tools for segmentation and feature extraction of Lossless derivative EEGIP London dataset.

Copy this 'seg_sta_nois' folder to the 'eegip/london/derivatives/lossless/derivatives' folder. 

Use EEGLAB with Matlab working directory set to:

eegip/london/derivatives/lossless

Add to the Matlab path:

addpath('code/dependencies/eeglab_asr_amica/');

Then start EEGLAB:

eeglab

To run the segmentation use the batch_context EEGLAB extension to execute the "seg_sta_dyn_dir_ind_nois.htb" script (located in 'derivatives/seg_sta_dyn_dir_ind_nois/code/scripts') on the *.qcr.set files in the lossless derivatives directory.

