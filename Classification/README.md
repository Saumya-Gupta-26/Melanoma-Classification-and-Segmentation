For classification, I have fine-tuned the VGG16 model pretrained on ImageNet dataset. All the layers except the last 4 layers are frozen. The parameters of the last 4 layers are learnt.

The data has been organized as follows:


data/

    train/
        benign/
              [1030 images]
        malignant/
              [270 images]
        
    test/
        benign/
              [350 images]
        malignant/
              [50 images]
              
    val/
        benign/
              [246 images]
        malignant/
              [54 images]
