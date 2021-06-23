# kitti

## prepare_data.py

### extract_frustum_data

没什么好说的，就说得到点云数据和吧、坐标系等信息，将其转换到图像坐标系的点云下，3维到2维的过程，随便得到2dbox 的2维点云数据

* 关于**R0_rect**，这个参数吧，我认为是从相机坐标系到图像坐标系的转换矩阵，反之亦然

```python

```

有一部分涉及到传感器坐标系，相机坐标系、图像坐标系，这里给个链接：

https://blog.csdn.net/xueluowutong/article/details/80950915

![img](https://img-blog.csdn.net/20180707144133312?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3h1ZWx1b3d1dG9uZw==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

其中，xy是图像坐标系，而uv坐标系是像素坐标系，离散量和连续量的区别

