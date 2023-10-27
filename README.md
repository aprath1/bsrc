# Benchmark for Surface Region Correspondence (BSRC)

This repo hosts the surface region correspondence evaluation dataset consisting of mulitple surface region ground truths for 3 object categories - Chair, Car and Plane.

Each object category has 10 objects with each object having 8 different ground truth surface regions. Providing 90 pairwise correspondence estimation possibility per category, with 8 region correspondences estimations in each pair. 

Sample images of surface region ground truths below:



| Chair | Car | Plane |
| ------ | ------ |------ |
| ![chair_regions](https://github.com/aprath1/bsrc/assets/88531660/0d9484f8-0bbc-450c-b899-f531ddfa3058) | ![car_regions](https://github.com/aprath1/bsrc/assets/88531660/05ec47b4-569d-4e2a-88e0-8698434f3d93) | ![plane_regions](https://github.com/aprath1/bsrc/assets/88531660/ec04acf8-b991-428d-91f6-3a2a28e1d948) |


NOTE1: This work is in ICRA conference submission. If accepted, after the review process, more code (data loaders and pretrained models), and details will follow - subject to approaval from the organization. 

NOTE2: This is a growing dataset and more objects categories and corresponding surface regions will be added gradually. Currently working on table object surface correspondence with improved NRDF, and preforming realworld robotic execution. This work is in processing fro European Robotics Forum (ERF) 2024. Videos and table dataset will be uploaded soon...
