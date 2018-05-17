# Background

The general objective of my brainhack project is to learn cortical thickness (CT) data processing and deep learning (DL). While I have aready published on CT data, I have used high-level parcels from Human connectome project (HCP), preprocessed by others. Given the expertise at this workshop, I would like to know the process from the start to parcel. This is also motivated by Mallar's comment, that once they run their preprocessing steps, CIVET will perform much better. Currently, we lost ~30% of the CT data due to QC issues. So far, I have not applied DL in my research.
My publication: https://doi.org/10.1101/204917
# The next step

The first step is to obtain preprocessing software from Mallar's web page.  He also offered their preprocessed actual CT data from the HCP. This would be a good validation data set, to make sure that I did everything correctly.

I will also apply the preprocessing pipeline to my own brain scan from participating in research. This will enable me to really start from 0 and create a surface for 3d-printing.

Finally, I will attempt to get a style transfer running to get my feed wet with DL.



# Specific learning objectives and deliverables
During the brainhack school, I'd like to 
  * preprocess my own brain using Mallar's pipeline
  * create a surface of my own brain with the help of Joane /Christopf
  * send it to 3d printer with the help of Christopf
  
  
  * send all HCP data for cleaning before CIVET using Mallar's pipeline
  * after that send HCP data to CIVET using Cbrain
  * after that compare results with previous our version, and perhaps also with Mallar's version

Finally, with DL
  * get DL working in my laptop, idelly in Rstudio
  * make a picture of result one and run it through the stylify pipeline
