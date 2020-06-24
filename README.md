# Infant_finer_segmentation
Please **read**this first: this repository is to segment infant brain MRI T2W scans in a finer scale. The output of our brain segmentation code contains 101 regions covering the whole brain. 

First, we ran the Developmental Human Connectome Project [**dHCP**] automated pipeline [https://github.com/BioMedIA/dhcp-structural-pipeline] for segmentation of T2w scans (Makropoulos et al., 2018). Then, for finer anatomical segmentation by lobe , we further subdivided grey matter from the frontal, parietal, and occipital lobes with a custom algorithm that utilizes a warped segmentation from the individual subject to an **AAL infant atlas** (Shi et al., 2011). 

