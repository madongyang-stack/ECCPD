# ECCPD
Convex and Compact Superpixels byEdge-Constrained Centroidal Power Diagram.

step1:
Run ECCPD.exe 


step2:
#  Enter the name of the image to be processed under the 'Input' folder：
==>40.jpg


step3:
#  Enter the number of superpixels：（300-3000）
==>1000



Note:


1.The results will be saved in the "output" folder .
2.The label will be saved under the "label" folder. 
3.The RCF image of the picture needs to be saved in the "rcf" folder. 
If you need to run an image other than the "input" folder example, you need to place the image in the "Input" folder and get the edge probability image (RCF) 
of the image and put it in the "rcf" folder. This program does not integrate RCF content, you need to run RCF as input, its code can be found in the link below. 
 (https://github.com/meteorshowers/RCF-pytorch)


