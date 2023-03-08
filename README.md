# STUNet
This is the code repository of the paper 'Symmetrical Transformer UNet for 3D Coronary Microvascular Segmentation'

Abstract. Automated 3D vessel segmentation helps physicians analyze, diagnose, and intervene in the coronary microvascula disease. Conventional methods on this task are prone to discontinuous and inaccurate results, especially for tiny vessel structures. To alleviate this, several works have combined the UNet-structured convolutional neural network (CNN) and transformers serially to improve the continuity and correctness by leveraging long-distance dependencies, i.e., the topological relationships of vessel fragments. Nevertheless, the serial architecture in which the CNN and transformer are bottlenecks to each other is not feasible to retaining both local and global information. In this work, we exploit the Symmetrical Transformer UNet (STUNet), a concise and scalable segmentation model, in which the CNN and transformer learn local and global features in a parallel manner. We also design a bidirectional attention fusion (BAF) module for local and global information interaction. Experimental results on one public dataset and two in-house datasets suggest: 1) Although achieving state-of-the-art results on all the metrics, STUNet shows very impressive average symmetric surface distance (ASSD) due to its capability of modelling sparse and anisotropic vessel structures. 2) STUNet has a more global receptive field than UNet, which is in consistent with our motivation.

What to open: The coronary microvascular segmentation models trained on our 500 samples, together with our codes, will be available after acceptance.
