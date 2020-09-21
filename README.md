# Skin-Lesion-Segmentation-LBCDN

The proposed framework employs the local binary convolution on U-Net architecture instead of the standard convolution in order to 
reduced-size deep convolutional encoder-decoder network that adopts loss function for robust segmentation. The proposed framework 
replaced the encoder part in U-net byLBCNN layers. The approach automatically learns and segments complex features of skin lesion 
images. The encoder stage learns the contextual information by extracting discriminative features while the decoder stagecaptures 
the lesion boundaries of the skin images. This addresses the issues with encoder-decoder networkproducing coarse segmented output 
with challenging skin lesions appearances such as low contrast between healthy and unhealthy tissues and fine grained variability. 
It also addresses issues with multi-size, multi-scaleand multi-resolution skin lesion images. The deep convolutional network also 
adopts a reduced-size networkwith just five levels of encoding-decoding network. 

 The proposed model records higher accuracy percentage and Jaccard index score of $97.09\%$ and $88.43\%$ on ISIC dataset respectivelly. 

References:  
 1- Local Binary Convolutional Neural Networks, Felix Juefei-Xu, Vishnu Naresh Boddeti, Marios Savvides; 
    Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2017, pp. 19-28.
    
 2- U-net: Convolutional networks for biomedical image segmentation. Ronneberger O, Fischer P, Brox T. In 
    International Conference on Medical image computing and computer-assisted intervention 2015 Oct 5 (pp. 234-241). Springer, Cham.
