# Experiments

### only with rgb
 ![image](Images/rgb.jpeg)

 ![image](Images/rgb_acc.jpeg)
 
-using only rgb we see good results with ‘rime’ and ‘dew’ but the accuracy is quite small compared to our final solution

### Only with hsv
 ![image](Images/hsv.jpeg)

 ![image](Images/rgb_acc.jpeg)
 
-this is the result for hsv alone, we can see some good results regarding ‘rime’, ‘dew’, ‘fogsmog’, ‘lightning’
-the accuracy is pretty decent but there are a lot of images which are not predicted correctly. The results are not that bad










### Rgb and hsv
 ![image](Images/rgb_hsv.jpeg)

 ![image](Images/rgb_hsv_acc.jpeg)
 
-the accuracy in this case is smaller than the previous case in which we tested only wich ‘hsv’, this is a little questionable but maybe when we work with such a lot of images and classes it’s a mixed blessing



### Onlty with frequency domain
 ![image](Images/freq.jpeg)
 
-in this case there are a lot of wrong predictions and the accuracy is pretty small but we can see the ‘fogsmog’ and ‘frost’ classes are our cup of tea




If we mess around with radius we got other accuracy, here is the accuracy with radius = 50:

 ![image](Images/radius_50.png)
 
Radius = 100:

 ![image](Images/radius_100.png)
 
Radius = 150:

 ![image](Images/radius_150.png)
 
After some tests our conclusion is that the best accuracy is when we set the radius to 108.


### Some images before and after converting to frequency domain:

![image](Images/0605.jpg) ![image](Images/0605_frequency.jpg)


![image](Images/2798.jpg) ![image](Images/2798_frequency.jpg)


### These images were predicted correct after converting them to frequency domain

![image](Images/right_pred.jpeg) ![image](Images/right_pred2.jpeg)  



### Final result
 ![image](Images/all.jpeg)
 
 ![image](Images/accuracy_all.jpeg)
 
-our final result is combining hsv, rgb, and frequency domain
