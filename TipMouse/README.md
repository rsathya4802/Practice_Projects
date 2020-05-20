# TipMouse - Now your laptop is in your Finger Tip !!

Another fun project using OpenCV where you can move your mouse cursor using your Finger Tip

**Steps followed**  
All these are implemented while capturing a Live Video from your Webcam 

1. Using **createBackgroundSubtractorMOG2()** to capture the background 
2. Subtracting current frame from background to get a frame containing only the user's hand
3. Drawing a Contour around the hand , the Finger Tip is found by considering the point which is the farthest away on the Contour from the Center
4. ***pyautogui*** is used to Move the cursor to the desired place after getting Co-ordinates of the Finger Tip


I am still working on improving the User Experience by making the it more accurate and smooth 