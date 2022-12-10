# beans
Experts from the National Crops Resources Research Institute in Uganda took pictures of various bean healthy and infected bean plants. In this dataset, there are three types of bean plants: healthy, infected with angular leaf spot disease, and bean rust disease.

In this project, I trained a Keras neural network model to classify a plant as healthy or having one of the two diseases in the dataset.

I used a sequential Keras model, trained over 100 epochs, batch size of 32, and used a validation set to track accuracy of the model over time. The final algorithm achieved an **accuracy of 78%.**

The applications of such a model are vast. In the future, a more sophisticated algorithm could be used on-board an agricultural drone, allowing for determination of which areas to spray with certain medicines. Additionally, this could allow farmers to detect disease outbreaks.