# Fruit-and-Vegetable-Image-Recognition-using-Deep-Learning
### Week-3 Project Assignment(Transfer Learning)

A fruit and vegetable classification dataset was taken up and trained to classify 10 fruits and 26 vegetables.

Our model uses a MobileNetV2 pretrained model in replacement for CNN. We have added a GlobalAveragePooling2D layer to reduce the dimensionality of the images, following which we have added 3 Dense layers, 2 of which have an activation of 'relu' and the other having 'softmax' activation'. The model is then compiled with optimizer to be 'adam' and loss function to be 'categorical_crossentropy'.

Our method of approach to increase accuracy was by using Data Augmentation and by increasing the number of layers in the model.

Current Training Accuracy | Current Validation Accuracy
------------------------- | ---------------------------
96.43% |96.38%

The fruits that we chose were as follows:
* Banana
* Apple
* Pear
* Grapes
* Orange
* Kiwi
* Watermelon
* Pomegranate
* Pineapple
* Mango

The vegetables that we chose were as follows:
* Cucumber
* Carrot
* Capsicum
* Onion
* Potato
* Lemon
* Tomato
* Raddish
* Beetroot
* Cabbage
* Lettuce
* Spinach
* Soy Bean
* Cauliflower
* Bell Pepper
* Chilli Pepper
* Turnip
* Corn
* Sweetcorn
* Sweet Potato
* Paprika
* Jalapeno
* Ginger
* Garlic
* Peas
* Eggplant
