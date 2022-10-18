# IC_Project
Image colorization using ResNet-18 on Flowers102 

We have used 6 layers of Resnet-18 and freezed their weights then we will proceed the training for the Network 

Algorithm:

    $RGB --> Lab color --> L-channel , A&B -channel 
                        
    L-channel --> Network --> A' & B' channel
Combining L and A'B' to get Lab image then converting it to RGB form
