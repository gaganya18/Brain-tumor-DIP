# Brain-tumor-detection-using-Matlab


Brain Tumor is a fatal disease which cannot be confidently detected without MRI. In the project, it is tried to detect whether patient’s brain has tumor or not from MRI image using MATLAB simulation. To pave the way for morphological operation on MRI image, the image was first  filtered using Anisotropic Diffusion Filter to reduce contrast between consecutive pixels. After that the image was resized and utilizing a threshold value image was converted to a black and white image manually. This primary filter the plausible locations for tumor presence. On this semi processed image morphological operations have been applied and information on solidity and areas of the plausible locations was obtained. A minimum value of both of this characters has been determined from statistical average of different MRI images containing tumor. Then it was used to deliver final detection result.

We have used the following methodology to build our project

![image](https://user-images.githubusercontent.com/95522162/205432669-8b42da14-f82b-4e48-9502-bbcff79ce5de.png)

INPUT IMAGE: This is the first step of the proposed system. The resulting MRI images may not be of very good quality for analysis. Images can be noisy, blurry, low-contrast. The area of interest can be difficult to extract .Here, grayscale MRI images are provided as input to the system

PREPROCESSING:  This is the initial processing of data in order to prepare them for primary processing or further analysis. The preprocessing phase of our project mainly includes those operations that are usually necessary before the target analysis and extraction of the necessary data and usually geometric corrections of the original image. These improvements include correcting information for jaggedness and unwanted noise in an area, removing an image of a non-brain element, and transforming the data so that it reflects correctly in the original image. The first preprocessing step is to transform this input MRI image into a suitable form with which further work can be done.

FEATURE EXTRACTION: It is the process by which certain features of interest  in an image are detected and presented for further processing. This is an important step in most computer vision and imaging solutions. Based on the results obtained during the extraction of signs, the tumor is classified. When extracting, certain parameters are taken into account: size, shape, composition, image location. This step extracts the Features of the given input image. Based on these characteristics, the image is analyzed and the area of the tumor is determined. 

IMAGE ANALYSIS:  The output is analyzed and displayed either as no tumor or tumor detected with its output

