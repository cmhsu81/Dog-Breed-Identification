# Dog-Breed-Identification_CSE598_Project

 ![](https://i.ibb.co/MDHcjJy/00c14d34a725db12068402e4ce714d4c.jpg)

Environment used :
```
OS: Windows 10
Software: MATLAB 2021b
```

1. First download the dataset from:
	- https://www.kaggle.com/c/dog-breed-identification/data

	- Counts for each breeds in the dataset:

	![](https://www.linkpicture.com/q/ResNet_CountBreeds.png)


2. Use this script to modify the dataset so it can be used by the networks:
	- ModifyDataset.mlx

3. Code, Visuals and ReadMe file for ResNet50V2 are in its own directory
	- /ResNet50V2

4. Other models were exported in its own live MATLAB script file.
	- Running the respective live scripts (notebooks) will load the network and start training:
		- TransferLearningAlexNet.mlx
		- TransferLearningAlexNetDesigner.mlx
		- TransferLearningGoogLeNetFinal.mlx
		- TransferLearningResNet18.mlx

4. Final trained networks, their output and workspace variables are stored in the respective .mat files, and can be imported in the workspace directly.
	- TransferLearningAlexNet.mat
	- TransferLearningAlexNetDesignerTest.mat
	- TransferLearningGoogLeNet.mat
	- AlexNet_params_2021_12_05__20_36_16.mat
	- GoogLeNetparams_2021_12_05__19_36_29.mat
	- ResNet18_params_2021_12_05__21_57_15.mat

5. Live scripts of manual validation are exported as both pdf and html.
