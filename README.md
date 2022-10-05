# Quantification-functional-tissue-units-human-body

~ Identifying and segmenting functional tissue units (FTUs) across five human organs.
~ Performing EDA and Feature extraction to analyze the various Functional organs.
~ Segmenting images and measuring features like area, perimeter, compactness, etc for each Functional tissues unit.


# STEPS PERFORMED :
1. I have a config class and utils file for basics.
2. The FTU class represents any one functional tissue unit as a shapely Polygon. It calculates features such as the area, perimeter, compactness, etc for each FTU.
3. The organ class represents any organ sample. The organ consists of a list of FTUs. It makes it easy to analyze any organ, perform EDA, and extract features.
4. I had shown example of one of each type of organs.


* Organ 10274 (Prostate)

num FTUs: 22
organ_type: prostate
pixel_size: 0.4
age: 76.0
sex: Male
data_source: HPA

![image](https://user-images.githubusercontent.com/80577092/194062043-c2f5d093-b359-47b6-871d-a892ab61d510.png)
![image](https://user-images.githubusercontent.com/80577092/194062108-9d5a3242-06f0-434b-923a-1d0df6bddae9.png)

* Organ 10392 (Spleen)

num FTUs: 4
organ_type: spleen
pixel_size: 0.4
age: 82.0
sex: Male
data_source: HPA

![image](https://user-images.githubusercontent.com/80577092/194062988-3d0153d3-945c-4ffe-bb52-4f4c1b19f366.png)
![image](https://user-images.githubusercontent.com/80577092/194063040-da23186b-4962-4205-8a39-923e2d5395db.png)

* Organ 10611 (Kidney)

num FTUs: 4
organ_type: kidney
pixel_size: 0.4
age: 68.0
sex: Female
data_source: HPA

![image](https://user-images.githubusercontent.com/80577092/194063157-74ef6778-5898-4051-8ea3-3df7ff66aba4.png)
![image](https://user-images.githubusercontent.com/80577092/194063196-01b99936-2d09-4c01-aa29-2d2f7e4572ae.png)

* Organ 10488 (Lung)

num FTUs: 2
organ_type: lung
pixel_size: 0.4
age: 78.0
sex: Male
data_source: HPA

![image](https://user-images.githubusercontent.com/80577092/194063258-5f18201f-1cca-4894-bf3c-dcf4c28eacfb.png)
![image](https://user-images.githubusercontent.com/80577092/194063330-0ab7a258-761a-4e16-ba09-5eccd08df020.png)

* Organ 10651 (Large Intestine)

num FTUs: 13
organ_type: largeintestine
pixel_size: 0.4
age: 83.0
sex: Male
data_source: HPA

![image](https://user-images.githubusercontent.com/80577092/194063382-06b7d2c0-54c1-4dc8-b3c0-2a0b52db064f.png)
![image](https://user-images.githubusercontent.com/80577092/194063446-798fd4cf-8e1f-4513-98cf-c54fd190cd76.png)

This work is under Process and not completed yet.
