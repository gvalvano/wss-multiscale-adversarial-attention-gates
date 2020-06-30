

## Don't miss any update!
**Subscribe to be notified when data and code will be released.** To fill out the subscription form, you must log in with your Google account. Alternatively, you can directly [contact us](https://gvalvano.github.io/wss-multiscale-adversarial-attention-gates/#contacts).

<iframe src="https://docs.google.com/forms/d/e/1FAIpQLSdXVFqMuc3Q_ojNkYWBkDNLd8sBNGjVkHw4oLx2xgZbN2EWXg/viewform?usp=sf_link" height="20%" width="80%" frameborder="0" marginheight="0" marginwidth="0">Loading…
</iframe>


## Abstract

[comment]: <> (<img align="right" src="https://github.com/gvalvano/wss-multiscale-adversarial-attention-gates/blob/master/method.pdf" width=100>)

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
**Weak Supervision** &nbsp; | &nbsp;
**Scribbles** &nbsp; | &nbsp;
**Segmentation** &nbsp; | &nbsp;
**GAN** &nbsp; | &nbsp;
**Attention** &nbsp; | &nbsp;
**Shape Priors**

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

-----------------------------
### Contacts

<style type="text/css">
span.spamprotection {display:none;}
</style>

<p>If you have any questions or suggestions, please write an email to:
gabriele&period;valvano<span class="spamprotection">dsadas</span>&#64; imtlucca&period;it . 
</p>
