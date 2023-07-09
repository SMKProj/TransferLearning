# TransferLearning
The project explores the utility of transfer learning, which is a technique where usability of predeveloped model is utilized in another machine learning task. For the purpose Mobilenet Predeveloped model is used in classification of tf_flowers dataset which is a collection of flowers images of various type.


While using Transfer learning, the last output layer of used model like here Mobilenet_v2 will not be used as there is difference of classes. For the purpose second most layer which is also called feature_extractor layer will be used and trainable value is set to False. The model is trained for 6 epochs and following results are achieved.

![image](https://github.com/SMKProj/TransferLearning/assets/85155952/3e5e7bba-f998-4dc7-a8b3-22f3c5f52573)

![image](https://github.com/SMKProj/TransferLearning/assets/85155952/8315e373-895c-44f6-b06e-0a00fbb44f81)


