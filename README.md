# Fast N-D Grayscale Image Segmenation With c- or Fuzzy c-Means

[![View Fast fuzzy c-means image segmentation on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://www.mathworks.com/matlabcentral/fileexchange/41967-fast-fuzzy-c-means-image-segmentation)

c-means and fuzzy c-means clustering are two very popular image segmentation algorithms. While their implementation is straightforward, if realized naively it will lead to substantial overhead in execution time and memory consumption. Although these deficiencies could be ignored for small 2D images they become more noticeable for large 3D datasets. This submission is intended to provide an efficient implementation of these algorithms for segmenting N-dimensional grayscale images. The computational efficiency is achieved by using the histogram of the image intensities during the clustering process instead of the raw image data. Finally, since the algorithms are implemented from scratch there are no dependencies on any auxiliary toolboxes.

For a quick demonstration of how to use the functions, run the attached `DemoFCM.m` file.

You can also get a copy of this repo from [Matlab Central File Exchange]. 

[Matlab Central File Exchange]: https://www.mathworks.com/matlabcentral/fileexchange/41967-fast-segmentation-of-n-dimensional-grayscale-images

## License
[MIT] © 2019 Anton Semechko 
a.semechko@gmail.com

[Image Processing Toolbox]: https://www.mathworks.com/products/image.html
[MIT]: https://github.com/AntonSemechko/Fast-Fuzzy-C-Means-Segmentation/blob/master/LICENSE.md
