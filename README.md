# Automatic-Image-Colorization
This project can colorize the grayscale image automatically. For this project used YUV color space. To colorize the image used two techniques: 
<br><br> 
**1.  Segmentation based coloring system and**
<br>
**2.  Without segmentation based coloring system.**
<br><br>
For segmentation based coloring system, we used SLIC segmentation algorithm to segment the similar color region of the input image. Linear Regression and SVR algorithm used to predict the U and V channel. Furthermore, For without segmentation based coloring system. we used  a deep learning model(CNN).

![image](https://user-images.githubusercontent.com/56289014/118141576-51914380-b42b-11eb-980e-4baf7f32f725.png)
![image](https://user-images.githubusercontent.com/56289014/118139939-b0ee5400-b429-11eb-8b14-5414e7af6900.png)
![image](https://user-images.githubusercontent.com/56289014/118139982-bfd50680-b429-11eb-85ec-9a1a6d5d75c4.png)
![image](https://user-images.githubusercontent.com/56289014/118140059-d4b19a00-b429-11eb-90e7-59399c9b92cc.png)
![image](https://user-images.githubusercontent.com/56289014/118140109-e1ce8900-b429-11eb-8566-18212c499831.png)

## 4. More Result

### 4.1 Result for Linear Regression(LR) model
![image](https://user-images.githubusercontent.com/56289014/118141997-c795aa80-b42b-11eb-8dfa-c017554104d1.png)
### 4.2 Result for Support Vector Regression(SVR) model
![image](https://user-images.githubusercontent.com/56289014/118142060-d7ad8a00-b42b-11eb-8fec-170363db94e2.png)
![image](https://user-images.githubusercontent.com/56289014/118142111-e431e280-b42b-11eb-900f-d49badc47a4c.png)
### 4.3 Result for Convolutional Neural Network(CNN)
![image](https://user-images.githubusercontent.com/56289014/118142292-0cb9dc80-b42c-11eb-9e7f-a1e0a9133aba.png)
![image](https://user-images.githubusercontent.com/56289014/118142351-1a6f6200-b42c-11eb-943b-d22ffd4a45a3.png)
