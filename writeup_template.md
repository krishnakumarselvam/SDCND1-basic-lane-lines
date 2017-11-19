# **Finding Lane Lines on the Road**

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report

---

### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. The functions are defined in [functions.py](functions.py)

> Convert image to Grayscale
<img src="img/step1.png" width="240" alt="Grayscale" />

> Added gaussian blur
<img src="img/step2.png" width="240" alt="Grayscale" />

> Canny edge detection
<img src="img/step3.png" width="240" alt="Grayscale" />

> Masking
<img src="img/step4.png" width="240" alt="Grayscale" />

> Hough transform
<img src="img/step5.png" width="240" alt="Grayscale" />

> Fit linear equation
<img src="img/step6.png" width="240" alt="Grayscale" />


### 2. Identify potential shortcomings with your current pipeline



### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
