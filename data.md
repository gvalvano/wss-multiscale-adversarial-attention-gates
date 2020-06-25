## Download

**We are working to make data available soon!**

If you use this data, please cite our paper as:
```
@article{valvano2020weakly,
  title={Weakly Supervised Segmentation with Multi-scale Adversarial Attention Gates},
  author={Valvano, Gabriele and Leo, Andrea and Tsaftaris, Sotirios A.},
  journal={},
  volume={},
  pages={},
  year={2020},
  publisher={}
}
```

## Data Description

###  ACDC
The 2017 Automatic Cardiac Diagnosis Challenge dataset [1] contains cine-MR images obtained by 100 patients with different MR scanners and acquisition protocols. 
Manual segmentations are provided along the images, containing pixel wise annotations for the end-diastolic (ED) and end-systolic (ES) cardiac phases. 
The annotated structures are left ventricle (LV), right ventricle (RV) and myocardium (MYO). 
Data can be downloaded [here](https://www.creatis.insa-lyon.fr/Challenge/acdc/index.html).

### Scribble Generation

To annotate the images with scribbles we used [ITK-SNAP](http://www.itksnap.org/pmwiki/pmwiki.php) [2]. 
We manually drew scribbles for RV, MYO, LV on top of the available segmentation masks provided in ACDC, for ES and ED phases. 
We additionally drew a scribble approximately around the heart to identify pixels belonging to the background class (BGD), while leaving the rest of the pixels 
unlabeled.  The average (standard deviation) image covarage of scribbles is:  0.1 (0.1)\%, 0.2 (0.1)\%, 0.1 (0.1)\% and 10.4 (8.4)\%, 
for RV, MYO, LV and BGD, respectively.

### Reference
[1] *O. Bernard, A. Lalande, C. Zotti, F. Cervenansky, X. Yang, P.-A. Heng, I. Cetin, K. Lekadir, O. Camara, M. A. G. Ballester et al., 
“Deep learning techniques for automatic MRI cardiac multi-structures segmentation and diagnosis: Is the problem solved?” 
IEEE TMI, vol. 37, no. 11, pp. 2514– 2525, 2018.*

[2] *P. A. Yushkevich, J. Piven, H. Cody Hazlett, R. Gimpel Smith, S. Ho, J. C. Gee, and G. Gerig, 
“User-Guided 3D Active Contour Segmentation of Anatomical Structures: Significantly Improved Efficiency and Reliability” 
Neuroimage, vol. 31, no. 3, pp. 1116–1128, 2006.*
