# Skin-Lesion-Segmentation-LBCDN

The proposed framework employs the local binary convolution on U-Net architecture instead of the standard convolution in order to 
reduced-size deep convolutional encoder-decoder network thatadopts loss function for robust segmentation. The proposed framework 
replaced the encoder part in U-net byLBCNN layers. The approach automatically learns and segments complex features of skin lesion 
images. Theencoder stage learns the contextual information by extracting discriminative features while the decoder stagecaptures 
the lesion boundaries of the skin images.  This addresses the issues with encoder-decoder networkproducing coarse segmented output 
with challenging skin lesions appearances such as low contrast betweenhealthy and unhealthy tissues and fine grained variability. 
It also addresses issues with multi-size, multi-scaleand multi-resolution skin lesion images. The deep convolutional network also 
adopts a reduced-size networkwith just five levels of encoding-decoding network. 
