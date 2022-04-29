# Investigating-the-Complexity-of-Deep-Neural-Networks

To train the Resnet-20 with AdderNet you will need the files "adder.py", "main.py", and "resmet20.py" Then using the following commands on Jupyter notebook:

import resnet20
import adder
%run main 

To test the model you will need "ResNet20-AdderNet.pth", "test.py" Then run the following command on Jupyter notebook

%run test.py --dataset cifar10 --model_dir '/Choose/Correct/Path/ResNet20-AdderNet.pth' --data_dir '/Choose/Correct/Path/To/Data'

A demo file called Demo_Run.ipynb shows the training and testing Results. 

The achieved training accuracy of AdderNet on CIFAR10 is 91.1200%
The achieved testing accuracy of AdderNet on CIFAR10 is 91.820%
The achieved testing accuracy of AdderNet on Modifed Drone-Vs-Bird is 88%
The achieved testing accuracy of the designed CNN on CIFAR10 is 81%


Preprocessing_Drone_Vs_Bird show the preprocessing steps perfromed on this dataset.
CNN_CIFAR10 shows the experiment done with the CNN model on CIFAR10, the file has the model summary and testing accuracy

------------------------------------------------------------------------------------------------------------------
Please note that these codes belong to AdderNet originally, very small modifications has been done on these codes.




	@article{AdderNet,
	title={AdderNet: Do We Really Need Multiplications in Deep Learning?},
	author={Chen, Hanting and Wang, Yunhe and Xu, Chunjing and Shi, Boxin and Xu, Chao and Tian, Qi and Xu, Chang},
	journal={CVPR},
	year={2020}
	}
