# Object Tracting on a Static Background
Here, we are tracking the position of an object on a static background. Such system can be use with videos to track the path of an object or a person.

# Processing Steps Applied
1. cv2.bilateralFilter
2. cv2.cvtColor (RGB to Gray)
3. cv2.absdiff
4. cv2.morphologyEx
5. cv2.threshold
6. cv2.medianBlur
7. cv2.findContours
8. cv2.drawContours

# Results
In the result we can clearly track the mouvement of the avenger picture from frame 1 to frame 2. Seeing that "black widow" hasn't moved, no detection has been made on it.
![Picture3](https://user-images.githubusercontent.com/48753146/157635809-b2f36e9f-4cc7-4d28-8010-491129cf31f1.png)


References:
Images have been downloaded separately and then modified:

https://www.stickpng.com/

https://resi.co.uk/advice/general/what-is-a-party-wall
