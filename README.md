# Image-based-plant-phenotyping: Localize and Detect Plants, Measure Projected Leaf Area and Perform Individual Leaf Segmentation

This project is a part of COMP9517 Computer Vision @UNSW, 2020

Phenotyping is one of the observable characteristics of plant for efficient and sustainable agriculture. Image based plant phenotyping is a growing application area of computer vision in agriculture. The key tasks are to identify plants, their species, localize their position as well as segment leaves to observe the projected area and segment all of the individual leaves in images. This paper focuses on the work done on the above mentioned tasks. The first task involves localizing each plant and its position. In that task, we apply connecting components algorithm and the distance metric to detect the plant and draw the bounding box of the plant. From that, we were able to get 82.27% average precision score for Ara2013-canon data set which is the highest among all the data sets we were provided. The second task is to measure the projected leaf area, where we use foreground extraction method with histogram threshold and binary threshold to extract the leaf area. From that, we observe a score of 94.47% on Dice similarity coefficient and 89.51% on the intersection over Union metric on overall data tray sets of
Ara2012 and Ara2013. The third task consists of segmenting individual leafs from a plant. This task is the most challenging aspect of this project since most of the leaves were overlapping due to similar appearance and shape characteristics. We attempt to solve it by using super-pixel segmentation and we then apply watershed segmentation to extract individual leaves. However, it wasn’t the best, shown by our low metric score of 44.0% of Symmetric Best Dice on overall data plant set of Ara2012, Ara2013 and Tobacco. This task was challenging as most of the leaves were overlapping, as they do share the same appearance and shape characteristics.

Refer to our paper "our_paper.pdf" for details.

## Files:
1) our_paper.pdf: Details of our work on image-based phant phenotyping
2) Codes: Our python implementaion
