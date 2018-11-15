# kaggle-airbus-ship
Participation to Airbus Kaggle competition
It is mostly a copy of the great work of https://www.kaggle.com/iafoss

With https://github.com/gaylordmarville/ we achieve to be 91th in the Private LeaderBoard : https://www.kaggle.com/c/airbus-ship-detection/leaderboard

- 01-ResNet34-training.ipynb : Train a ResNet34 to classify boat / no boat in pictures
- 02-Unet34-train.ipynb : Use the ResNet34 to build a UNet34 to do a semantic segmentation on boat
- 03-Unet34-submission.ipynb : Use the UNet34 to make the prediction and compute the submission to Kaggle