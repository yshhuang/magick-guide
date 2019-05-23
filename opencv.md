---
title: 学习OpenCV4(二)-数字盲水印
tags: c++ 图像处理 OpenCV 
key: 20190514
published: false
---

### 背景
#### 三角函数
1. 三角函数之正交性
 $$
\int_{-π}^π\sin{mx}\sin{nx}\mathrm{d}x=\begin{cases}
0,\quad for\quad m \neq n \\\\
π,\quad for\quad m = n
\end{cases}
$$

1. 
[证明](https://ocw.chu.edu.tw/pluginfile.php/861/mod_resource/content/14/Summary_259.pdf)
<!-- 数字图像,信号处理,傅里叶变换 -->

### java实现
1. 读入原图
Mat是OpenCV最常用的类,用它来存储一个图片的所有信息.先记下原图的宽高,后面会用到
```java
Mat inputImg=imread(inputImage);
int w=inputImg.cols();
int h=inputImg.rows();
```

2. 优化尺寸

```java
public static Mat optimizeMatSize(Mat mat) {
        Mat padded=new Mat();
        Core.copyMakeBorder(mat,padded,0,mat.rows() % 2,0,mat.cols() % 2,Core.BORDER_CONSTANT,Scalar.all(0));
        return padded;
    }
```


