# Awesome Satellite Imagery Competitions [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)  

List of machine learning competitions for satellite imagery and remote sensing. Sorted by submission deadline.

![](header_img.jpg)  

- [**Spacenet Challenge - Round 4**](
https://spacenetchallenge.github.io/datasets/spacenet-OffNadir-summary.html) *(CosmiQ Works, DigitalGlobe, Radiant Solutions, AWS, Dec 2018)*  
Building object detection with Off-Nadir imagery. 126k building polygons (Atlanta). 27 WorldView 2 images from 7-54 degrees off-nadir angle. Bi-cubicly resampled to same number of pixels in each tile despite courser native resolution due to high off-nadir angles.

- [**Open AI Challenge: Tanzania**](https://competitions.codalab.org/competitions/20100#learn_the_details-overview) *(WeRobotics & Wordlbank, Nov 2018)*  
Building object detection & building condition classification (3 classes), RGB UAV imagery - [Link to data](https://docs.google.com/spreadsheets/d/1kHZo2KA0-VtCCcC5tL4N0SpyoxnvH7mLbybZIHZGTfE/edit#gid=0)   

- [**Airbus Ship Detection Challenge**](https://www.kaggle.com/c/airbus-ship-detection) *(Airbus, Sep 2018)*   
Ship Object Detection, 104k train / 88k test image chips, object pixel masks in run-length encoding format, Kaggle kernels.

- [**Agricultural Crop Cover Classification Challenge**](https://crowdanalytix.com/contests/agricultural-crop-cover-classification-challenge) *(CrowdANALYTIX, Jul 2018)*  
Semantic Segmentation (2 main categories: Corn, Soybeans), Landsat 8 imagery (30m), USDA Cropland Data Layer as ground truth.

- [**DOTA: Large-scale Dataset for Object Detection in Aerial Images**](https://captain-whu.github.io/DOTA/index.html) *(Wuhan University et al.)*  
Object Detection (15 categories), 188k instances, Google Earth image chips, Faster-RCNN baseline model (MXNet), DOTA development kit, Academic use only   

- [**xView 2018 Detection Challenge**](http://xviewdataset.org) *(DIUx, Jul 2018)*  
Object Detection (60 categories), 1 million instances, Worldview-3 imagery (0.3m), COCO data format, pre-trained Tensorflow and Pytorch baseline models

- [**CrowdAI Mapping Challenge**](https://www.crowdai.org/challenges/mapping-challenge) *(Humanity & Inclusion NGO, May 2018)*  
Semantic/Instance Segmentation (buildings), RGB sat. imagery, COCO data format

- [**Open AI Challenge: Aerial Imagery of South Pacific Islands**](https://blog.werobotics.org/2018/01/11/open-ai-challenge-2/) *(WeRobotics & Worldbank, May 2018)*  
Object Detection (4 tree species), Semantic Segmentation (2 road types), RGB UAV imagery (0.4/0.8m), multiple AOIs in Tonga

- [**DEEPGLOBE - 2018 Satellite Challange**](http://deepglobe.org/index.html) *(CVPR, Apr 2018)*  
3 challenge tracks: Road Extraction, Building Detection, Land cover classification

- [**IEEE Data Fusion Contest 2018**](http://www.grss-ieee.org/community/technical-committees/data-fusion/data-fusion-contest/) *(IEEE, -Mar 2018)*  
Land cover classification (20 categories) by fusing data three sources: Multispectral LiDAR, Hyperspectral (1m), RGB imagery (0.05m)

- [**Spacenet Challenge - Round 3**](https://spacenetchallenge.github.io/Competitions/Competition3.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, Feb 2018)*  
Road Extraction, multiple city aois, 3(RGB)/8band Worldview-3 imagery (0.3m), SpaceNet Challenge Asset Library

- [**Statoil/C-CORE Iceberg Classifier Challenge**](https://www.kaggle.com/c/statoil-iceberg-classifier-challenge) *(Statoil/C-CORE, Jan 2018)*  
Image Recognition (Predict if image chip contains ship or iceberg), 2-band HH/HV polarization SAR imagery, Kaggle kernels

- [**Functional Map of the World Challenge**](https://www.iarpa.gov/challenges/fmow.html) *(IARPA, Dec 2017)*  
Object Detection (63 categories), 1 million instances, 4/8 band sat. imagery, COCO data format, baseline models

- [**Urban 3D Challenge**](https://www.topcoder.com/urban3d) *(USSOCOM, Dec 2017)*    
Building footprint detection, RGB orthophotos (0.5m), 3 cities, SpaceNet Challenge Asset Library

- [**NIST DSE Plant Identification with NEON Remote Sensing Data**](https://www.ecodse.org) *(inria.fr, Oct 2017)*  
Extraction of tree position, species and crown parameters, hyperspectral (1m) & RGB imagery (0.25m), LiDAR point cloud and canopy height model

- [**Planet: Understanding the Amazon from Space**](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space) *(Planet, Jul 2017)*  
Image recognition (Predict 1 of 13 land cover and 1 of 4 cloud condition labels per image chip), Amazonian rainforest, 4 band sat. imagery (RGB-NIR, 3-5m), Kaggle kernels    

- [**TiSeLaC : Time Series Land Cover Classification Challenge**](https://sites.google.com/site/dinoienco/tiselc) *(UMR TETIS, Jul 2017)*  
Land cover time series classification (9 categories), Landsat-8 (30m, 23 images time series, 10 band features), Reunion island   

- [**NOAA Fisheries Steller Sea Lion Population Count**](https://www.kaggle.com/c/noaa-fisheries-steller-sea-lion-population-count) *(NOAA, Jun 2017)*  
Object Detection (5 sea lion categories), ~ 80k instances, ~ 1k aerial images, Kaggle kernels  

- [**Spacenet Challenge - Round 2**](https://spacenetchallenge.github.io/Competitions/Competition2.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, May 2017)*  
Building extraction, multiple city aois, 3/8band Worldview-3 imagery (0.3m), SpaceNet Challenge Asset Library

- [**DSTL Satellite Imagery Feature Detection challenge**](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection) *(Dstl, Feb 2017)*  
Object Detection & Classification (10 categories). 3/16 band Worldview 3 imagery (0.3m - 7.5m), Kaggle kernels

- [**Spacenet Challenge - Round 1**](https://spacenetchallenge.github.io/Competitions/Competition1.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, Jan 2017)*  
Building extraction, Rio de Janeiro, 3/8band Worldview-3 imagery (0.5m mosaic), SpaceNet Challenge Asset Library

- [**Multi-View Stereo 3D Mapping Challenge**](https://www.iarpa.gov/challenges/3dchallenge.html) *(IARPA, Nov 2016)*  
Develop of a Multi-View Stereo (MVS) 3D mapping algorithm that can convert high-resolution satellite images to 3D point clouds

- [**Draper Satellite Image Chronology**](https://www.kaggle.com/c/draper-satellite-image-chronology) *(Draper, Jun 2016)*  
Predict the chronological order of images taken at the same locations over 5 days, Kaggle kernels

- [**Inria Aerial Image Labeling**](https://project.inria.fr/aerialimagelabeling/contest/) *(inria.fr)*  
Semantic Segmentation (buildings), RGB aerial imagery (0.3m), 5 cities
