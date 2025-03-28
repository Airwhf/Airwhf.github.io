---
title:          "ISAT v2.0: an integrated tool for nested-domain configurations and model-ready emission inventories for WRF-AQM"
date:           2023-04-13 00:01:00 +0800
selected:       false
pub:            "Geoscientific Model Development (GMD)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-custom badge-success">Spotlight</span>'
pub_date:       "2023"

abstract: >-
  The ISAT (Inventory Spatial Allocation Tool) v2.0 is an integrated tool that has been developed to configure nested domains, downscale regional emission inventories, allocate local emission inventories, and generate model-ready emission inventories for the Weather Research and Forecasting (WRF)–Air Quality Numerical Model (AQM). The tool consists of four modules, namely “Prepgrid”, “Downscale”, “Mapinv”, and “Prepmodel”, which are designed to perform specific tasks. The Prepgrid module utilizes a nested-domain configuration algorithm based on WRF-AQM nested rules and the target domain shapefile. The Downscale module establishes a “sub-grid nearest” method to downscale the regional emission inventory based on spatial surrogate, thereby improving the accuracy and computational efficiency of the process. The Mapinv module allocates a user-defined regional- and/or city-level emission inventory to grid level based on the target domain shapefile and the spatial surrogate. Finally, the Prepmodel module generates the model-ready inventories by introducing unique user-friendly emission sector IDs using abbreviations and speciation profiles based on species in the emission inventory and chemical mechanisms, which is available for both the CMAQ and CAMx models. The ISAT v2.0 tool provides a user-friendly solution for model users to configure and run WRF-AQM. And it provides a framework and related algorithms for researchers to develop similar tools for WRF-AQM.
# cover:          assets/images/covers/cover3.jpg
authors:
  - Kun Wang
  - Chao Gao
  - Kai Wu
  - Kaiyun Liu
  - Haofan Wang
  - Mo Dan
  - Xiaohui Ji
  - Qingqing Tong
links:
  Unsplash: https://gmd.copernicus.org/articles/16/1961/2023/
---
