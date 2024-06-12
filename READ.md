# Brain Tumor MRI Classification Using Pre-trained Models

## What is a brain tumor?
A brain tumor is a collection, or mass, of abnormal cells in your brain. Your skull, which encloses your brain, is very rigid. Any growth inside such a restricted space can cause problems. Brain tumors can be cancerous (malignant) or noncancerous (benign). When benign or malignant tumors grow, they can cause the pressure inside your skull to increase. This can cause brain damage, and it can be life-threatening.

### Significance
Early detection and classification of brain tumors is an important research domain in the field of medical imaging and accordingly helps in selecting the most convenient treatment method to save patients life therefore.

#### Dataset Details
This dataset contains 7022 images of human brain MRI images which are classified into 4 classes:
1) glioma
2) meningioma
3) no tumor
4) pituitary
About 22% of the images are intended for model testing and the rest for model training. Pay attention that The size of the images in this dataset is different. You can resize images to the desired size after pre-processing and removing the extra margins.

##### Data Pre-processing
Crop the part of the image that contains only the brain (which is the most important part of the image): The cropping technique is used to find the extreme top, bottom, left and right points of the brain using OpenCV.
You can do this with Preprocessing.py

##### Acknowledgments:
This work is inspired by the advancements in AI-driven drug discovery and the contributions of researchers in the field. Special thanks to the developers of open-source libraries and datasets used in this project. References:

https://aspire10x.com/data-solutions/

I used ResNet50 as pretrained model 

### Contact/correspondance:
For any inquiries or feedback, please contact sharmar@aspire10x.com. https://aspire10x.com/data-solutions/

