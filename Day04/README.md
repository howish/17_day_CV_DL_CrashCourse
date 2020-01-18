# Note

## What's new for me:
- cv2.threshold: Opencv's thresholding is surprisingly powerful. [[doc](https://docs.opencv.org/master/d7/d4d/tutorial_py_thresholding.html)]
    - cv2.THRESH_BINARY: Global threshold.
    - cv2.ADAPTIVE_THRESH_MEAN_C: Local threshold compute by local mean value.
    - cv2.ADAPTIVE_THRESH_GAUSSIAN_C: Local threshold compute by local gaussian-weighted sum.
    - cv2.THRESH_OTSU: Global threshold with automatically computed threshold.
- cv2.boundingRect: Find a tilted bounding box fitting the given points. 