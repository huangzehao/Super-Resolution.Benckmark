# Super-Resolution.Benckmark
A curated list of super-resolution resources and a benchmark for single image super-resolution algorithms.

## State-of-the-art algorithms
 * ScSR [[Web]](http://www.ifp.illinois.edu/~jyang29/ScSR.htm)
  * Image super-resolution as sparse representation of raw image patches (CVPR2008), Jianchao Yang et al.
  * Image super-resolution via sparse representation (TIP2010), Jianchao Yang et al.
  * Coupled dictionary training for image super-resolution (TIP2011), Jianchao Yang et al.
 * ANR [[Web]](http://www.vision.ee.ethz.ch/~timofter/ICCV2013_ID1774_SUPPLEMENTARY/index.html)
  * Anchored Neighborhood Regression for Fast Example-Based Super-Resolution (ICCV2013), Radu Timofte et al.
 * A+ [[Web]](http://www.vision.ee.ethz.ch/~timofter/ACCV2014_ID820_SUPPLEMENTARY/)
  * A+: Adjusted Anchored Neighborhood Regression for Fast Super-Resolution (ACCV2014), Radu Timofte et al.
 * IA [[Web]](http://www.vision.ee.ethz.ch/~timofter/CVPR2016_ID769_SUPPLEMENTARY/index.html)
  * Seven ways to improve example-based single image super resolution (CVPR2016), Radu Timofte et al.
 * SelfExSR [[Web]](https://sites.google.com/site/jbhuang0604/publications/struct_sr)
  * Single Image Super-Resolution from Transformed Self-Exemplars (CVPR2015), Jia-Bin Huang et al.
 * NBSRF [[Web]](http://jordisalvador-image.blogspot.com/2015/08/iccv-2015.html)
  * Naive Bayes Super-Resolution Forest (ICCV2015), Jordi Salvador et al.
 * SRCNN [[Web]](http://mmlab.ie.cuhk.edu.hk/projects/SRCNN.html)
  * Image Super-Resolution Using Deep Convolutional Networks (ECCV2014), Chao Dong et al.
  * Image Super-Resolution Using Deep Convolutional Networks (TPAMI2015), Chao Dong et al.
 * CSCN [[Web]](http://www.ifp.illinois.edu/~dingliu2/iccv15/)
  * Deep Networks for Image Super-Resolution with Sparse Prior (ICCV2015), Zhaowen Wang et al.
  * Robust Single Image Super-Resolution via Deep Networks with Sparse Prior (TIP2016), Ding Liu et al.
 * VDSR [[Unofficial Implementation by huangzehao]](https://github.com/huangzehao/caffe-vdsr)
  * Accurate Image Super-Resolution Using Very Deep Convolutional Networks (CVPR2016), Jiwon Kim et al.
 * DRCN
  * Deeply-Recursive Convolutional Network for Image Super-Resolution (CVPR2016), Jiwon Kim et al. 
 
## Datasets

| Test Dataset | Image source |
|---- | ---|----|
| **Set 5** |  [Bevilacqua et al. BMVC 2012](http://people.rennes.inria.fr/Aline.Roumy/results/SR_BMVC12.html)  |
| **Set 14** |  [Zeyde et al. LNCS 2010](https://sites.google.com/site/romanzeyde/research-interests)  |
| **BSD 100** | [Martin et al. ICCV 2001](https://www.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/) |
| **Urban 100** | [Huang et al. CVPR 2015](https://sites.google.com/site/jbhuang0604/publications/struct_sr)  |

| Train Dataset | Image source |
|---- | ---|----|
| **Yang 91** |  [Yang et al. CVPR 2008](http://www.ifp.illinois.edu/~jyang29/ScSR.htm)  |
| **BSD 200** | [Martin et al. ICCV 2001](https://www.eecs.berkeley.edu/Research/Projects/CS/vision/bsds/) |

## Quantitative comparisons

##### Results on Set 5

|  Scale    | Bicubic | A+  | SRCNN | SelfExSR | CSCN | VDSR | DRCN |
|:---------:|:-------:|:--------:|:------:|:----:|:----:|:----:|
| **2x** - PSNR/SSIM|   33.66/0.9929	|   36.54/0.9544	|   36.66/0.9542	|   36.49/0.9537	|  36.93/0.9552	|  37.53/0.9587	|  37.63/0.9588	|    
| **3x** - PSNR/SSIM|   30.39/0.8682	|   32.59/0.9088	|   32.75/0.9090	|   32.58/0.9093	|  33.10/0.9144	|  33.66/0.9213	|  33.82/0.9226	|  
| **4x** - PSNR/SSIM|   28.42/0.8104	|   30.28/0.8603	|   30.48/0.8628	|   30.31/0.8619	|  30.86/0.8732	|  31.35/0.8838	|  31.53/0.8854	|  
