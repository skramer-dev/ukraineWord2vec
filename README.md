# ukraineWord2vec

Code for visualization was taken from https://towardsdatascience.com/visualizing-word-embedding-with-pca-and-t-sne-961a692509f5

Two seperate sets of words were fed into the model: <br>
'Ukraine, Russia, sanction, Crimea, Donbass'<br>
'Kiev, drone, missile, army, target'<br>

In order to be able to visualize the different word vectors a dimensionality reduction via PCA had to be run before plotting the data


Google News 100bil pretrained word similarities:
![newplot](https://user-images.githubusercontent.com/81179144/166687098-1136776d-0c04-4a4c-bf21-b21b7b30cbf9.png) 
![newplot](https://user-images.githubusercontent.com/81179144/166687278-a5038033-e2d9-4214-ae5b-637cd1362748.png)



Google News 100bil pretrained and additional fine tuning on selected speeches from Zelensky word similarities:

![newplot](https://user-images.githubusercontent.com/81179144/167444017-8c12aab7-3646-4112-a81a-2b45dce98057.png)
![newplot](https://user-images.githubusercontent.com/81179144/167444247-efc8c8a4-5d34-4ace-bd0b-a566030598de.png)
