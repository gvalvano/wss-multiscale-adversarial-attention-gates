
## Abstract
Large, fine-grained image segmentation datasets, annotated at pixel-level, are difficult to obtain, 
particularly in medical imaging, where annotations also require expert knowledge. 
Weakly-supervised learning can train models by relying on weaker forms of annotation, such as scribbles. 
Here, we learn to segment using scribble annotations in an adversarial game. With unpaired segmentation masks, 
we train a multiscale GAN to generate realistic segmentation masks at multiple resolutions, while we use scribbles 
to learn the correct position in the image. Central to the model’s success is a novel attention
gating mechanism, which we condition with adversarial signals to act as a shape prior, resulting in better object 
localization at multiple scales. We evaluated our model on several medical (ACDC, LVSC, CHAOS) and non-medical (PPSS) datasets, and
we report performance levels matching those achieved by models trained with fully annotated segmentation masks. We also 
demonstrate extensions in a variety of settings: semi-supervised learning; combining multiple scribble sources 
(a crowdsourcing scenario) and multi-task learning (combining scribble and mask supervision). We will release expert-made 
scribble annotations for the ACDC dataset, and the code used for the experiments here.

## Keywords
Weak Supervision, Scribbles, Segmentation, GAN, Attention, Shape Priors.

## Cite us:
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
