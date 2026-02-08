# Virtual Lab for LiDAR Point Cloud Analysis using Laserfarm Workflow

Quantifying ecosystem structure is essential for sustainable forest management, species distribution research, dynamic ecosystem modelling, and biodiversity monitoring. Recent years have seen a rapid surge in the use of light detection and ranging (LiDAR) technology for characterizing the structure of ecosystems. Yet, a key bottleneck is the availability of free and open-source tools that allow a standardized processing of large amounts of LiDAR point clouds in an efficient and distributed way. Here, we integrate a high-throughput workflow called "Laserfarm" into NaaVRE, enabling the efficient, scalable, and distributed processing of LiDAR point clouds from national and regional airborne laser scanning (ALS) surveys into geospatial data products of ecosystem structure. 

## Description

This Virtual Lab allows users to easily generate vegetation structural properties from LiDAR point clouds using a standardized and scalable workflow. The aim is to make ready-to-use LiDAR processing pipelines accessible, enabling ecologists and researchers to integrate detailed ecosystem structural information from complex 3D point clouds into their studies without the burden of handling large ALS datasets and computational challenges. Free and open-source [Laserchicken software](https://laserchicken.readthedocs.io/en/latest/) and the [Lasefarm workflow](https://laserfarm.readthedocs.io/en/latest/index.html) have been implemented in this Virtual Lab using the NaaVRE technique, allowing efficient, standardized yet customizable processing of 3D point clouds into user-defined LiDAR-derived vegetation metrics. Meanwhile, these tools are run in the cloud, leveraging the performance and flexibility of cloud computing. 

## Keywords

* Essential biodiversity variable
* Ecosystem structure
* Airborne laser scanning
* Vegetation metrics
* Horizontal and vertical properties
* Ecosystem dynamics
* High-throughput workflow
* Distributed computing


## Features

* Automated and efficient LiDAR metrics calculation pipeline by [Laserfarm](https://github.com/eEcoLiDAR/Laserfarm) 
* 50 + commonly used LiDAR metrics provided by [Laserchicken](https://github.com/eEcoLiDAR/laserchicken)
* Scalable and distributed processing in cloud infrastructures powered by [NaaVRE](https://naavre.net/)


## Tutorial

A tutorial is available in [NaaVRE](https://beta.naavre.net/vreapp/vl/laserfarm) in [vl_laserfarm/Documentation](https://github.com/NaaVRE/vl-laserfarm/blob/main/Laserfarm.ipynb) (need to be updated)


## Laserfarm

[Laserfarm](https://pypi.org/project/laserfarm/) is a reproducible, modular end-to-end workflow for efficiently extracting LiDAR metrics of ecosystem structure on distributed computing infrastructures. The four modular scriptable pipelines allow the standardized and computationally efficient re-tiling, normalization, feature extraction, and rasterization of LiDAR point clouds into high-resolution geospatial data products of ecosystem structure. 

![Oost_LiDAR_BIOMAC](https://github.com/user-attachments/assets/8226b533-995f-4315-aea4-d0644dae5ddc)


## Publications

1. Kissling, W. D., Shi, Y., Koma, Z., Meijer, C., Ku, O., Nattino, F., Seijmonsbergen, A. C., and Grootes, M. W.: Laserfarm – A high-throughput workflow for generating geospatial data products of ecosystem structure from airborne laser scanning point clouds, Ecol. Inform., 72, 101836, 2022. <https://doi.org/10.1016/j.ecoinf.2022.101836>.
2. Meijer, C., Grootes, M. W., Koma, Z., Dzigan, Y., Gonçalves, R., Andela, B., van den Oord, G., Ranguelova, E., Renaud, N., and Kissling, W. D.: Laserchicken – A tool for distributed feature calculation from massive LiDAR point cloud datasets, SoftwareX, 12, 100626, 2020. <https://doi.org/10.1016/j.softx.2020.100626>.
3. Shi, Y., Wang, J., and Kissling, W. D.: Multi-temporal high-resolution data products of ecosystem structure derived from country-wide airborne laser scanning surveys of the Netherlands, Earth Syst. Sci. Data, 17, 3641–3677, 2025. <https://doi.org/10.5194/essd-17-3641-2025>.




  
