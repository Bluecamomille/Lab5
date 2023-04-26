# Computer Vision in Remote Sensing

![](https://media.giphy.com/media/Ju7l5y9osyymQ/giphy.gif)

Computer vision can be used in remote sensing geographic information system (GIS) for natural disaster management. Some computer vision methods that can be used are feature extraction, classification methods, change detection, and Support Vector Machines (SVMs). 
These methods are discussed and demonstrated in the following sources:
-	Survey of computer vision-based natural disaster warning systems, by ByoungChul Ko and Sooyeong Kwak 
-	Satellite remote sensing as a tool in disaster management and sustainable development: toward a synergistic approach, by Olalekan Mumin Bello, Yusuf Adedoyin Aina
-	UAV strategies validation and remote sensing data for damage assessment in post-disaster scenarios by A. Calantropio, F. Chiabrando, G Sammartano, A. Spano, L. Teppati Lose

Feature extraction is a computer vision method where identification and extraction of specific features or patterns is derived from an image. Typically, the edges, corners, and texture of that image are analyzed. (Pakalniskis, 5) This process can be automatic or semi-automatic. This method was used for post damage assessment with the goal of analyzing the whole 3D development of the building, meaning that both the roofing and facades are studied. (Calantropio, 121) There are instances where the roof has very low damages, but the facades sustained significantly more damages and vice versa. It is important to study all aspect of a building for accurate results. 

For instance, the classification method was used for damage assessment in Accumoli, Italy. The classification method is when each pixel in an image is assigned a specific land cover and land use class based on its spectral characteristics. (Pakalniskis, 7) This specific building in Accumoli was classified as “Negligible to slight damage” according to the Copernicus EMS and nadir point of view. However, the UAVs 3D model shows “Negligible to slight damage” on the roof of the building, but the facade of the building sustained significantly more damage which was not identified through nadir point of view. 

Change detection is another computer vision method in remote sensing. This method requires two or more images of the same area taken at different times to compare and identify changes that occurred. (Pakalniskis, 8) For maximal accuracy, it is important that the images are of the exact same location. The growth of very high resolution data has enhanced the use and quality of remotely sensed data in disaster relief management. 

<img width="412" alt="image" src="https://user-images.githubusercontent.com/127626824/234705182-7e58eadf-cbad-4e1f-a806-3a06104398f5.png">(Bello, 7)

Here is an example of an image taken before and after a tsunami. The changes are very obvious to the bare eye, but analysis of smaller areas can also be done.  

“Wildfire smoke detection, using video cameras, is challenging because the main characteristics of smoke are constantly uncertain, vague patterns of shape and color.” (Ko, 4) Smoke detection based on support vector machines (SVMs) is more accurate and effective. SVMs are machine learning algorithm that can be used for classification purposes. A hyperplane is created in a high-dimensional space to separate the different classes as much as possible. (Pakalniskis, 11) This method is often used for object detection, in this case smoke detection. From the input image the algorithm will detect color, texture, motion, and shape as feature extraction. This data is then put in a classifier learning, and finally into fire classification.

<img width="428" alt="image" src="https://user-images.githubusercontent.com/127626824/234705312-40e26a33-7270-46e8-bd81-5c8648bf8069.png">(Ko, 6)

This figure showcases the capacity of SMVs to differentiate wildfire smoke and smoke-colored clouds. 


Sources: 
Bello, Olalekan Mumin, and Yusuf Adedoyin Aina. “Satellite Remote Sensing as a Tool in Disaster Management and Sustainable Development: Towards a Synergistic Approach.” Procedia - Social and Behavioral Sciences, vol. 120, 2014, pp. 365–373., https://doi.org/10.1016/j.sbspro.2014.02.114. 
Calantropio, A., et al. “UAV Strategies Validation and Remote Sensing Data for Damage Assessment in POST-DISASTER Scenarios.” The International Archives of the Photogrammetry, Remote Sensing and Spatial Information Sciences, XLII-3/W4, 2018, pp. 121–128., https://doi.org/10.5194/isprs-archives-xlii-3-w4-121-2018. 
Ko, ByoungChul, and Sooyeong Kwak . “Survey of Computer Vision–Based Natural Disaster Warning Systems.” Optical Engineering, vol. 51, no. 7, 2012, p. 070901., https://doi.org/10.1117/1.oe.51.7.070901. 
![image](https://user-images.githubusercontent.com/127626824/234705801-78f357bc-a1df-45e1-b66e-58b2eb1557d7.png)

