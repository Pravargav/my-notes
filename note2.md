#How to open pycharm project
----------------------------
Always open pycharm from file manager open as pycharm project then only terminal opens unless terminal cannot open as local

#Image data generator
----------------------------
Imagedatagenarator doesnot add new augmented images(5) to the existing original image(1) containint directory.ie.5+1 =6 in directory is false.
it generates 5 images of exisitin single image virtually not physically and use those 5 virtual images for training not the single image in the directory used for training.
->directory name: dir
->directory has only one image for training 
->dir/img.jpg
->after using image generator 
->diretory: dir/img.jpg no change 
->but 5 virtual images generated using img.jpg virtually img1,img2...img5 and deleted automatically after training 

#Input Size
---------------------------
->the input size given in Image Data Generator ex-(224,224,3) must be the same size input data that should be used in Model input size like conn2d(inputssize=(244,244,3))

#Attributes order
----------------------------
->The order of attributes is important in nlp
ex-(a=a,b=b,c=c) is different from(a=a,c=c,b=b)
->that is nlp is attribute-order or permutation sensitive

#Axis value in nlp
-------------------------------
->change the values of axis -1,0,1 etc. and check the answer in Coursera Nlp.
