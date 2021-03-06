# Image Filters 图像滤波器

> 通过本教程，你将学到：
> + 什么是图像滤波器？
> + `cv::blur,` `cv::guassianBlur`,`cv::..`函数的使用方式

图像的本质是数字信号，图像滤波器就是对图像这一类数字信号进行滤波操作的操作子。 
卷积运算是滤波器的基础。
 
通过本教程你将学会使用以下几类图像滤波器进行图像去噪：
+ Normalized Box Filter (Average Filter) 均值滤波器
+ Gaussian Filter 高斯滤波器
+ Median Filter 中值滤波器
+ Bilateral Filter 双边滤波器

## Tutorial Source 来源
[official tutorial 图像平滑处理](http://www.opencv.org.cn/opencvdoc/2.3.2/html/doc/tutorials/imgproc/gausian_median_blur_bilateral_filter/gausian_median_blur_bilateral_filter.html#smoothing)

[official tutorial 实现自己的线性滤波器](http://www.opencv.org.cn/opencvdoc/2.3.2/html/doc/tutorials/imgproc/imgtrans/filter_2d/filter_2d.html#filter-2d)
## Other References 其他参考资料