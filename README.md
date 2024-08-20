# IC_Project
Image colorization using ResNet-18 on Flowers102 

We have used 6 layers of Resnet-18 and freezed their weights then we will proceed the training for the Network 

Algorithm:

    RGB --> Lab  color space image --> L-channel , A&B -channel 
                        
    L-channel --> Network --> A' & B' channel
    
    L + A'B' --> lab image --> RGB
    
![image](https://github.com/user-attachments/assets/a0323130-474b-4801-86f9-4cae460981b5)
![image](https://github.com/user-attachments/assets/57543fbd-3fa4-42ee-9ce2-d8e5f160b61d)
