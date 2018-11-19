# Awesome Satellite Imagery Datasets [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)  

List of aerial and satellite imagery datasets with annotations for computer vision and deep learning. Newest datasets at the top of each category (Instance segmentation, object detection, semantic segmentation, chip classification, other).   

![](header_img.jpg)  


### Instance Segmentation   

- [**Spacenet Challenge Round 4 - Off-nadir**](
https://spacenetchallenge.github.io/datasets/spacenet-OffNadir-summary.html) *(CosmiQ Works, DigitalGlobe, Radiant Solutions, AWS, **Dec 2018**)*   
126k building footprints (Atlanta), 27 WorldView 2 images (0.3m res.) from 7-54 degrees off-nadir angle. Bi-cubicly resampled to same number of pixels in each image to counter courser native resolution with higher off-nadir angles.  

- [**Airbus Ship Detection Challenge**](https://www.kaggle.com/c/airbus-ship-detection) *(Airbus, **Nov 2018**)*   
131k ships, 104k train / 88k test image chips, satellite imagery (1.5m res.), raster mask labels in in run-length encoding format, Kaggle kernels.   

- [**Open AI Challenge: Tanzania**](https://competitions.codalab.org/competitions/20100#learn_the_details-overview) *(WeRobotics & Wordlbank, **Nov 2018**)*   
Building footprints & 3 building conditions, RGB UAV imagery - [Link to data](https://docs.google.com/spreadsheets/d/1kHZo2KA0-VtCCcC5tL4N0SpyoxnvH7mLbybZIHZGTfE/edit#gid=0)   

- [**Netherlands LPIS agricultural field boundaries**](https://www.pdok.nl/introductie?articleid=1948958) *(Netherlands Department for Economic Affairs)*   
294 crop/vegetation catgeories, 780k parcels, yearly dataset for 2009-2018. Open the [atom feed downloadlinks](http://geodata.nationaalgeoregister.nl/brpgewaspercelen/atom/brpgewaspercelen.xml) with Firefox etc., not Chrome. 

- [**Denmark LPIS agricultural field boundaries**](https://kortdata.fvm.dk/download/Markblokke_Marker?page=MarkerHistoriske) *(Denmark Department for Agriculture)*   
293 crop/vegetation catgeories, 600k parcels, yearly dataset for 2008-2018   

- [**CrowdAI Mapping Challenge**](https://www.crowdai.org/challenges/mapping-challenge) *(Humanity & Inclusion NGO, May 2018)*  
Buildings footprints, RGB satellite imagery, COCO data format   

- [**Spacenet Challenge Round 2 - Buildings**](https://spacenetchallenge.github.io/datasets/spacenetBuildings-V2summary.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, May 2017)*  
685k building footprints, 3/8band Worldview-3 imagery (0.3m res.), 5 cities, SpaceNet Challenge Asset Library   

- [**Spacenet Challenge Round 1 - Buildings**](https://spacenetchallenge.github.io/datasets/spacenetBuildings-V1summary.html) *(CosmiQ Works, Radiant Solutions, NVIDIA, Jan 2017)*  
Building footprints (Rio de Janeiro), 3/8band Worldview-3 imagery (0.5m res.), SpaceNet Challenge Asset Library   


### Object Detection   

- [**DOTA: Large-scale Dataset for Object Detection in Aerial Images**](https://captain-whu.github.io/DOTA/index.html) *(Wuhan University et al.)*  
15 categories from plane to bridge, 188k instances, Google Earth image chips, Faster-RCNN baseline model (MXNet), DOTA development kit, Academic use only      

- [**xView 2018 Detection Challenge**](http://xviewdataset.org) *(DIUx, Jul 2018)*   
60 categories from helicopter to stadium, 1 million instances, Worldview-3 imagery (0.3m res.), COCO data format, pre-trained Tensorflow and Pytorch baseline models   

- [**Open AI Challenge: Aerial Imagery of South Pacific Islands**](https://docs.google.com/document/d/16kKik2clGutKejU8uqZevNY6JALf4aVk2ELxLeR-msQ/edit) *(WeRobotics & Worldbank, May 2018)*  
Tree position & 4 tree species, RGB UAV imagery (0.4m/0.8m res.), multiple AOIs in Tonga   

- [**NIST DSE Plant Identification with NEON Remote Sensing Data**](https://www.ecodse.org) *(inria.fr, Oct 2017)*  
Tree position, tree species and crown parameters, hyperspectral (1m res.) & RGB imagery (0.25m res.), LiDAR point cloud and canopy height model   

- [**NOAA Fisheries Steller Sea Lion Population Count**](https://www.kaggle.com/c/noaa-fisheries-steller-sea-lion-population-count) *(NOAA, Jun 2017)*  
5 sea lion categories, ~ 80k instances, ~ 1k aerial images, Kaggle kernels   

- [**Spacenet Rio De Janeiro Points of Interest Dataset**](https://spacenetchallenge.github.io/datasets/spacenetPOI-summary.html) *(CosmiQ Works, Radiant Solutions, Jan 2017)*  
460 categories from airfield to internet cafes, 120k points (11k manually confirmed), 3/8band Worldview-3 imagery (0.5m res.), SpaceNet Challenge Asset Library   

- [**Cars Overhead With Context (COWC)**](https://gdo152.llnl.gov/cowc/) *(Lawrence Livermore National Laboratory)*   
32k car bounding boxes, aerial imagery (0.15m res.), 6 cities    


### Semantic Segmentation   

- [**Agricultural Crop Cover Classification Challenge**](https://crowdanalytix.com/contests/agricultural-crop-cover-classification-challenge) *(CrowdANALYTIX, Jul 2018)*  
2 main categories corn and soybeans, Landsat 8 imagery (30m res.), USDA Cropland Data Layer as ground truth.   

- [**Spacenet Challenge Round 3 - Roads**](https://spacenetchallenge.github.io/datasets/spacenetRoads-summary.html) *(CosmiQ Works, Radiant Solutions, Feb 2018)*   
8000 km of roads in 5 city aois, 3/8band Worldview-3 imagery (0.3m res.), SpaceNet Challenge Asset Library   

- [**Urban 3D Challenge**](https://www.topcoder.com/urban3d) *(USSOCOM, Dec 2017)*    
157k building footprints, RGB orthophotos (0.5m res.), DSM/DTM, 3 cities, SpaceNet Challenge Asset Library   

- [**DSTL Satellite Imagery Feature Detection Challenge**](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection) *(Dstl, Feb 2017)*  
10 land cover categories from crops to vehicle small, 57 1x1km images, 3/16-band Worldview 3 imagery (0.3m-7.5m res.), Kaggle kernels   

- [**Inria Aerial Image Labeling**](https://project.inria.fr/aerialimagelabeling/contest/) *(inria)*  
Semantic Segmentation (buildings), RGB aerial imagery (0.3m res.), 5 cities   

- [**ISPRS Potsdam 2D Semantic Labeling Contest**](http://www2.isprs.org/commissions/comm3/wg4/2d-sem-label-potsdam.html) *(ISPRS)*   
6 urban land cover classes, raster mask labels, 4-band RGB-IR aerial imagery (0.05m res.) & DSM, 38 image patches     


### Chip classification (Image Recognition)   

- [**Alibaba Cloud German AI Challenge 2018**](https://tianchi.aliyun.com/competition/introduction.htm?raceId=231683&_lang=en_US) *(StepStone, DLR, Alibaba Cloud, Tianchi, Jan 2018)*   
Local climate zone classification, 17 categories (10 urban e.g. compact high-rise, 7 rural e.g. scattered trees), 400k 32x32 pixel chips covering 42 cities (LCZ42 dataset), Sentinel 2 & Sentinel 1 (both 10m res.)   

- [**Statoil/C-CORE Iceberg Classifier Challenge**](https://www.kaggle.com/c/statoil-iceberg-classifier-challenge) *(Statoil/C-CORE, Jan 2018)*  
2 categories ship and iceberg, 2-band HH/HV polarization SAR imagery, Kaggle kernels   

- [**Functional Map of the World Challenge**](https://www.iarpa.gov/challenges/fmow.html) *(IARPA, Dec 2017)*  
63 categories from solar farms to shopping malls, 1 million chips, 4/8 band satellite imagery (0.3m res.), COCO data format, baseline models   

- [**Planet: Understanding the Amazon from Space**](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space) *(Planet, Jul 2017)*  
13 land cover categories + 4 cloud condition categories, 4-band (RGB-NIR) satelitte imagery (5m res.), Amazonian rainforest, Kaggle kernels    

- [**Deepsat: SAT-4/SAT-6 airborne datasets**](https://csc.lsu.edu/~saikat/deepsat/) *(Louisiana State University, 2015)*   
6 land cover categories, 400k 28x28 pixel chips, 4-band RGBNIR aerial imagery (1m res.) extracted from the 2009 National Agriculture Imagery Program (NAIP)   

- [**UC Merced Land Use Dataset**](http://weegee.vision.ucmerced.edu/datasets/landuse.html) *(UC Merced, Oct 2010)*   
21 land cover categories from agricultural to parkinglot, 100 chips per class, aerial imagery (0.30m res.)   


### Other Focus / Multiple Tasks   

- [**DEEPGLOBE - 2018 Satellite Challange**](http://deepglobe.org/index.html) *(CVPR, Apr 2018)*  
Three challenge tracks: Road Extraction, Building Detection, Land cover classification   

- [**IEEE Data Fusion Contest 2018**](http://www.grss-ieee.org/community/technical-committees/data-fusion/data-fusion-contest/) *(IEEE, -Mar 2018)*  
20 land cover categories by fusing data three sources: Multispectral LiDAR, Hyperspectral (1m), RGB imagery (0.05m res.)   

- [**TiSeLaC : Time Series Land Cover Classification Challenge**](https://sites.google.com/site/dinoienco/tiselc) *(UMR TETIS, Jul 2017)*  
Land cover time series classification (9 categories), Landsat-8 (23 images time series, 10 band features, 30m res.), Reunion island   

- [**Multi-View Stereo 3D Mapping Challenge**](https://www.iarpa.gov/challenges/3dchallenge.html) *(IARPA, Nov 2016)*  
Develop a Multi-View Stereo (MVS) 3D mapping algorithm that can convert high-resolution Worldview-3 satellite images to 3D point clouds, 0.2m lidar ground truth data.   

- [**Draper Satellite Image Chronology**](https://www.kaggle.com/c/draper-satellite-image-chronology) *(Draper, Jun 2016)*  
Predict the chronological order of images taken at the same locations over 5 days, Kaggle kernels   