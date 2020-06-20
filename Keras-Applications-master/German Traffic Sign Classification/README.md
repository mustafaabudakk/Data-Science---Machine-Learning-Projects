## <b>German Traffic Sign Recognition</b>

In this project, I've built and trained a deep neural network to classify traffic signs using Tensorflow-Keras.
I have used <a href="https://www.kaggle.com/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign">German Traffic Sign Dataset</a> where the bounding box locations and labels for traffic signs are provided. Here is a random sample of images:

![00000_00000_00000](https://user-images.githubusercontent.com/40672298/84037857-d7994480-a9a7-11ea-883d-b7c198ae8f54.png)
![00000_00000_00017](https://user-images.githubusercontent.com/40672298/84037862-d8ca7180-a9a7-11ea-96fc-0549b51fd7b8.png)
![00001_00000_00000](https://user-images.githubusercontent.com/40672298/84037996-01eb0200-a9a8-11ea-8f70-fd3129b79372.png)
![00001_00000_00028](https://user-images.githubusercontent.com/40672298/84038000-02839880-a9a8-11ea-90eb-e6f2ca5757a3.png)
![00001_00001_00029](https://user-images.githubusercontent.com/40672298/84038002-031c2f00-a9a8-11ea-9c04-b32667dd3c65.png)
![00013_00000_00029](https://user-images.githubusercontent.com/40672298/84038079-19c28600-a9a8-11ea-8559-b048571a5f54.png)
![00013_00001_00029](https://user-images.githubusercontent.com/40672298/84038081-1a5b1c80-a9a8-11ea-94ec-92d567a73cbf.png)
![00023_00000_00029](https://user-images.githubusercontent.com/40672298/84038100-247d1b00-a9a8-11ea-968e-572a79a603e6.png)
![00023_00001_00004](https://user-images.githubusercontent.com/40672298/84038104-2515b180-a9a8-11ea-8713-6492d4b4115e.png)
![00035_00000_00026](https://user-images.githubusercontent.com/40672298/84038116-2c3cbf80-a9a8-11ea-9c5c-91e65055f6aa.png)

Summary of data set:

- The size of training set is 31367
- The size of the validation set is 7842
- The size of test set is 12631
- The shape of a traffic sign image is (32, 32, 3)
- The number of unique classes/labels in the data set is 43

