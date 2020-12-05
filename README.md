# Aerial Template Matching Dataset

This data accompanies the publication "Assisting UAV Localization via Deep Contextual Image Matching Using Semi-Local Constraints". For further details, read the paper.

Following is the structure of folders:

- data - Contains a total of 2052 images of three areas. More information in the paper.
- orthomosaic - Contains orthomosaics of three areas made from the images in the 'data' folder
- satellite-orthomosaic - Contains orthomosaics for the same three areas but made using Bing Satellite Data from OpenLayers in QGIS. Please note correspondances for these orthomosaics are not given.
- labels.csv - Contains pairs of points of correspondance between orthomosaics and images in 'data' folder.

Images from file 'Image1' to 'Image1200' belong to NUST Islamabad area.<br/>
Images from file 'Image1201' to 'Image1680' belong to DHA Islamabad area.<br/>
Images from file 'Image1681' to 'Image2052' belong to GujarKhan District area.<br/>

To download dataset:

```
git clone https://github.com/m-hamza-mughal/aerial-template-matching-dataset.git
cd aerial-template-matching-dataset
bash download.sh
```

For queries, contact:
Hamza Mughal
mmughal.bee15seecs@seecs.edu.pk
