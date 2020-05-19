## Canny Edge Detector 

 This is a Canny Edge Detector written in Python with the help of **OpenCV** which can detect edges in a given image  
 Live video edge detection is also implemented  
 
 **Steps followed**   
 1. Using **Sobel filter** to get change in pixels along the direction of both x and y axes   
 2. **Non-max supression** to remove unwanted pixels
 3. Categorise left over pixels into Strong and Weak with the help of a thershold
 4. **Hysterisis**: Out of the Weak pixels , the ones which have a Strong pixel adjacent to them are retained

**Output**  
* Before  
    ![Before](before.jpg)  
* After     
    ![Before](after)
