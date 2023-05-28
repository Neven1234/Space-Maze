# Space-Maze
***We need to classify EOG signals to control the movements of the Player.*** 
> **First, we make some pre-processing on EOG signals, WE apply butter band pass on it and then we down sample the signals by 50**

> **Second, we need to extract featuers from the output data from the pre-processing stage, So we use 2 ways, first way we use wavlets to extract approx. and details featuers and apply some statiscal operations on the output from the wavelets and the second way is to use The power spectral density(PSD) after using the wavelets**

> **After the extraction of the featuers, we use that featuers to train the model, we try CatBoost, Random forest, KNN and logistic regression, the winner of the highest accuracy is Catboost model**

> **After trainning we save the model to use in the game**

***Game interface***
> **1D.py game and that the game in the console**
> 
> **game.py a game with an interface but without EOG signals**
> 
> **game-basedon-EOG and that the game using the EOG signals**
