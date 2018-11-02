# Awesome Satellite Imagery Datasets [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)  

List of aerial and satellite imagery datasets for computer vision and deep learning. Instance segmentation, object detection, semantic segmentation, chip classification and other tasks. Newest datasets at the top of each category.   

![](header_img.jpg)  


### Instance Segmentation   

- [**Spacenet Challenge Round 4**](
https://spacenetchallenge.github.io/datasets/spacenet-OffNadir-summary.html) *(CosmiQ Works, DigitalGlobe, Radiant Solutions, AWS, **Dec 2018**)*   
126k building footprints (Atlanta), 27 0.3m res. WorldView 2 images from 7-54 degrees off-nadir angle. Bi-cubicly resampled to same number of pixels in each image to counter courser native resolution with higher off-nadir angles.  

- [**Airbus Ship Detection Challenge**](https://www.kaggle.com/c/airbus-ship-detection) *(Airbus, **Nov 2018**)*   
131,030 ships, 104k train / 88k test image chips, 1.5m res. satellite imagery, raster mask labels in in run-length encoding format, Kaggle kernels.   

- [**Open AI Challenge: Tanzania**](https://competitions.codalab.org/competitions/20100#learn_the_details-overview) *(WeRobotics & Wordlbank, **Nov 2018**)*   
Building footprints & 3 building conditions, RGB UAV imagery - [Link to data](https://docs.google.com/spreadsheets/d/1kHZo2KA0-VtCCcC5tL4N0SpyoxnvH7mLbybZIHZGTfE/edit#gid=0)  

- [**CrowdAI Mapping Challenge**](https://www.crowdai.org/challenges/mapping-challenge) *(Humanity & Inclusion NGO, May 2018)*  
Buildings footprints, RGB satelitte imagery, COCO data format   

- [**Spacenet Challenge Round 2**](https://spacenetchallenge.github.io/datasets/spacenetBuildings-V2summary.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, May 2017)*  
685,000 building footprints, 0.3m res. 3/8band Worldview-3 imagery, multiple cities, SpaceNet Challenge Asset Library   

- [**Spacenet Challenge Round 1**](https://spacenetchallenge.github.io/datasets/spacenetBuildings-V1summary.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, Jan 2017)*  
Building footprints (Rio de Janeiro), 0.5m res. 3/8band Worldview-3 imagery, SpaceNet Challenge Asset Library   


### Object Detection   

- [**DOTA: Large-scale Dataset for Object Detection in Aerial Images**](https://captain-whu.github.io/DOTA/index.html) *(Wuhan University et al.)*  
15 categories from plane to bridge, 188k instances, Google Earth image chips, Faster-RCNN baseline model (MXNet), DOTA development kit, Academic use only      

- [**xView 2018 Detection Challenge**](http://xviewdataset.org) *(DIUx, Jul 2018)*   
60 categories from helicopter to stadium, 1 million instances, 0.3m res. Worldview-3 imagery, COCO data format, pre-trained Tensorflow and Pytorch baseline models   

- [**Open AI Challenge: Aerial Imagery of South Pacific Islands**](https://docs.google.com/document/d/16kKik2clGutKejU8uqZevNY6JALf4aVk2ELxLeR-msQ/edit) *(WeRobotics & Worldbank, May 2018)*  
Tree position & 4 tree species, 0.4m/0.8m res. RGB UAV imagery, multiple AOIs in Tonga   

- [**NIST DSE Plant Identification with NEON Remote Sensing Data**](https://www.ecodse.org) *(inria.fr, Oct 2017)*  
Tree position, tree species and crown parameters, hyperspectral (1m) & 0.25m RGB imagery, LiDAR point cloud and canopy height model   

- [**NOAA Fisheries Steller Sea Lion Population Count**](https://www.kaggle.com/c/noaa-fisheries-steller-sea-lion-population-count) *(NOAA, Jun 2017)*  
5 sea lion categories, ~ 80k instances, ~ 1k aerial images, Kaggle kernels   


### Semantic Segmentation   

- [**Agricultural Crop Cover Classification Challenge**](https://crowdanalytix.com/contests/agricultural-crop-cover-classification-challenge) *(CrowdANALYTIX, Jul 2018)*  
2 main categories corn and soybeans, 30m res. Landsat 8 imagery, USDA Cropland Data Layer as ground truth.   

- [**Spacenet Challenge Round 3**](https://spacenetchallenge.github.io/Competitions/Competition3.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, Feb 2018)*  
Road Extraction, multiple city aois, 0.3m res. 3/8band Worldview-3 imagery, SpaceNet Challenge Asset Library   

- [**Urban 3D Challenge**](https://www.topcoder.com/urban3d) *(USSOCOM, Dec 2017)*    
Building footprint detection, RGB orthophotos (0.5m), 3 cities, SpaceNet Challenge Asset Library   

- [**DSTL Satellite Imagery Feature Detection challenge**](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection) *(Dstl, Feb 2017)*  
10 categories, 57 1x1km images, 0.3m-7.5m res. 3/16-band Worldview 3 imagery, Kaggle kernels   

- [**Inria Aerial Image Labeling**](https://project.inria.fr/aerialimagelabeling/contest/) *(inria.fr)*  
Semantic Segmentation (buildings), RGB aerial imagery (0.3m), 5 cities   


### Chip classification (Image Recognition)   

- [**Statoil/C-CORE Iceberg Classifier Challenge**](https://www.kaggle.com/c/statoil-iceberg-classifier-challenge) *(Statoil/C-CORE, Jan 2018)*  
2 categories ship and iceberg, 2-band HH/HV polarization SAR imagery, Kaggle kernels   

- [**Functional Map of the World Challenge**](https://www.iarpa.gov/challenges/fmow.html) *(IARPA, Dec 2017)*  
63 categories from solar farms to shopping malls, 1 million chips, 0.3m res. 4/8 band satellite imagery, COCO data format, baseline models   

- [**Planet: Understanding the Amazon from Space**](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space) *(Planet, Jul 2017)*  
13 land cover categories + 4 cloud condition categories, 5m res. 4-band (RGB-NIR) satelitte imagery, Amazonian rainforest, Kaggle kernels    


### Other Focus / Multiple Tasks   

- [**DEEPGLOBE - 2018 Satellite Challange**](http://deepglobe.org/index.html) *(CVPR, Apr 2018)*  
3 challenge tracks: Road Extraction, Building Detection, Land cover classification   

- [**IEEE Data Fusion Contest 2018**](http://www.grss-ieee.org/community/technical-committees/data-fusion/data-fusion-contest/) *(IEEE, -Mar 2018)*  
20 land cover categories by fusing data three sources: Multispectral LiDAR, Hyperspectral (1m), RGB imagery (0.05m)   

- [**TiSeLaC : Time Series Land Cover Classification Challenge**](https://sites.google.com/site/dinoienco/tiselc) *(UMR TETIS, Jul 2017)*  
Land cover time series classification (9 categories), Landsat-8 (30m, 23 images time series, 10 band features), Reunion island   

- [**Multi-View Stereo 3D Mapping Challenge**](https://www.iarpa.gov/challenges/3dchallenge.html) *(IARPA, Nov 2016)*  
Develop a Multi-View Stereo (MVS) 3D mapping algorithm that can convert high-resolution satellite images to 3D point clouds   

- [**Draper Satellite Image Chronology**](https://www.kaggle.com/c/draper-satellite-image-chronology) *(Draper, Jun 2016)*  
Predict the chronological order of images taken at the same locations over 5 days, Kaggle kernels   