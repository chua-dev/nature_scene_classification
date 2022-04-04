# nature_scene_classification

Ever wonder how Huawei or other latest phone camera recognize scenery image? Yes, thru Deep Learning, we can give computer an eye. 
There are total 6 classes for buildings, forest, glacier, mountain, sea, street

I try to use CNN neural network and achieve good train accuracy first 99.07% train acc, yet only managed to get 77.07 val acc.

In the free time, I will try to perfect this model with different DL architecture

27/3/22 - 99.07% ta | 77.07% va  
31/3/22 - 96.49% ta | 78.97% va  
4/4/22 - 83.85% ta | 72.57% va

Remarks  
31/3/22 - Added bunch of BatchNormal and Dropout normalization to layers, it does increase val acc slightly (up to 81%), but lower train accuracy  
4/4/22 - Highly lower layer complexity and 0.0001 learning rate, train with 200 epoch with early stopping callback, to no avail
