The general objective of my brainhack project is to learn **cortical thickness (CT) data processing** and **deep learning (DL)**. 

# Background
## CT

I have previous experience with CT, as I have already pulished a previous paper. At the same time, there I used high-level parcels from Human connectome project (HCP), preprocessed by others. Given the expertise at this workshop, I would like to know the CT otaining  process from the start to parcel. This is also motivated by Mallar's comment, that once they run their preprocessing steps, CIVET will perform much better. Currently, we lost ~30% of the CT data due to QC issues.

My publication: https://doi.org/10.1101/204917.

To make the CT pipeline more personal, my secondary goal is to 3D print my own brain, for which I have a T1.

## DL

So far, I have not applied DL in my research. However, I would like to use DL layers to test various theoretical considerantions in personality, which could also apply for brain data.

# The next steps

##CT in HCP

 - [x] Obtain T1 weighted data from HCP, young adult S1200 release. This is availale for me at the MNI. 
 	*  the file formats are .mnc and .nii
 - [x] get a CIVET account
 - [ ] get Mallar's pipeline working in Docker or lab linux computer
 - [ ] (optional) - obtain HCP processed data from Mallar's lab
 - [ ] practice on one dataset (my brain)
 - [ ] run script on the HCP dataset
 	- [ ] first run Mallar's script
 	- [ ] then run CIVET script
 - [ ] compare the number of people passed in original CIVET run, Mallar's script + CIVET and Mallar's HCP cleaning effort
 - [ ] compare the people passed in one, and not passed in another, to understand the type of errors passed with the advanced pipeline
 - [ ] run published analysis again with new data, to see if and how the results change. 

## CT 3d print
 - [ ] obtain surface files for freesurfer
 - [ ] talk to Sebastian on how to send the surface files to printer
 - [ ] print brains
 - [ ] ...
 - [ ] profit!

## DL

The goal is to get my feet wet with DL and learn how to rearrange layers for my goals. Therefore, I will apply DL for some simple goals, but also more complex ones.
- [x] get DL working in R, as I am more familiar with R
- [x] make a beautiful brain-art picture
- [ ] make a photo of my printed brain and convert that into an art picture

### non-brain DL

The overearching theme for personality psychology is in fact rather similar to brain reserach  - do we need high order personality traits / brain parcels or low-order personality traits/brain parcels? The criterium should be predicting interesting phenotypes, like obesity, alcohol consumption, or other health behaviours.

 - [x] obtain personality-outcome data (N=3500)
 - [ ] figure out the way to configure neuronal layers to correspond to certain theoretical limits (5 factors, 30 facets, interactions/moderations)
 - [ ] run the modes

