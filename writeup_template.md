# **Finding Lane Lines on the Road**

---

**Finding Lane Lines on the Road**

The goals / steps of this project are the following:
* Make a pipeline that finds lane lines on the road
* Reflect on your work in a written report

---
### Output

* [Video 1](https://youtu.be/mnNc1lqebHI)
* [Video 2](https://youtu.be/3iS_FffYM_k)
---
### Reflection

### 1. Describe your pipeline. As part of the description, explain how you modified the draw_lines() function.

My pipeline consisted of 5 steps. The functions are defined in [functions.py](functions.py)

> Convert image to Grayscale
<img src="img/step1.png" width="240" alt="Grayscale" />

> Added gaussian blur (kernel_size = 5)
<img src="img/step2.png" width="240" alt="Grayscale" />

> Canny edge detection (thresholds = (50, 150))
<img src="img/step3.png" width="240" alt="Grayscale" />

> Masking
<img src="img/step4.png" width="240" alt="Grayscale" />

> Hough transform
(rho = 2, theta = pi / 180, threshold = 15,
min_line_length = 40, max_line_gap = 20)
<img src="img/step5.png" width="240" alt="Grayscale" />

> Fit linear equation
<img src="img/step6.png" width="240" alt="Grayscale" />

The results are also averaged over 5 frames (trailing) when the pipeline is run for videos.

### 2. Identify potential shortcomings with your current pipeline



### 3. Suggest possible improvements to your pipeline

A possible improvement would be to ...

Another potential improvement could be to ...
