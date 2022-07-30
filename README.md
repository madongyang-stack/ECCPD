# ECCPD
# Convex and Compact Superpixels by Edge-Constrained Centroidal Power Diagram.
# Dongyang Ma, Yuanfeng Zhou, Shiqing Xin, Wenping Wang:Convex and Compact Superpixels by Edge- Constrained Centroidal Power Diagram. IEEE Trans. Image Process. 30: 1825-1839 (2021)

This is the first version of our project (no post-processing). 

step1:
Run ECCPD.exe 


step2:
Enter the name of the image to be processed under the 'Input' folder：
==>40.jpg


step3:
Enter the number of superpixels：（300-3000）
==>1000



Note:


1.The results will be saved in the "output" folder .
2.The label will be saved under the "label" folder. 
3.The RCF image of the picture needs to be saved in the "rcf" folder. 
If you need to run an image other than the "input" folder example, you need to place the image in the "Input" folder and get the edge probability image (RCF) 
of the image and put it in the "rcf" folder. This program does not integrate RCF content, you need to run RCF as input, its code can be found in the link below. 
 (https://github.com/meteorshowers/RCF-pytorch)

Note that the program can only process one image at a time, requiring you to enter the name of the image and the number of superpixels required. For your convenience, I made a program 'https://github.com/madongyang-stack/ECCPD_batch' that can be batch processed, so you just need to enter the number of superpixels you want into cpd.exe. However, you need to put images and RCFs into the 'Input' and 'rcf' folders in advance.  
# If you need help, please email 2024335573@qq.com
