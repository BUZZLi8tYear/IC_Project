# IC_Project
Image colorization using ResNet-18 on Flowers102 

We have used 6 layers of Resnet-18 and freezed their weights then we will proceed the training for the Network 

Algorithm:

    RGB --> Lab  color space image --> L-channel , A&B -channel 
                        
    L-channel --> Network --> A' & B' channel
    
    L + A'B' --> lab image --> RGB
    
