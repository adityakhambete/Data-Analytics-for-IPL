# Periocular-Recognition-Library
## Motivation.
Due to a mandation of face masks, using authentication systems has become a necessity . Thus, this library helps you in registering an user and using a face authentication service 
whilst wearing a face mask. 

## How to use this Library
You will only need to files from this repositiory viz [Recognise a person](https://github.com/adityakhambete/Periocular-Recognition-Library/blob/master/recognisePerson.py)
and [Register a new person](https://github.com/adityakhambete/Periocular-Recognition-Library/blob/master/registerNewPerson.py)

Please remember to update the model so that the new user is stored into the existing database. This will increase the accuracy of recognizing the new user.
To update a model [use this file](https://github.com/adityakhambete/Periocular-Recognition-Library/blob/master/addNewLabel.py) and then the model will be trained 
once you [run this file](https://github.com/adityakhambete/Periocular-Recognition-Library/blob/master/trainUpdatedModel.py)
Also once you enter a new image into the database you will need to use [get Embeddings file](https://github.com/adityakhambete/Periocular-Recognition-Library/blob/master/getEmbeddings.py) to convert images into embeddings


All of the other files are the backend of this project. Feel free to explore them. 
More about the theory in the Theory Readme file.
The Dataset was taken from an opensource platform with additional images taken from a smartphone camera.

Note that the original dataset can be downloaded [using this link](http://iris.di.ubi.pt/ubipr.html) 

## Registering an user
We have provided bounding boxes which will turn green if the image is captured correctly. There will be a total of five images that will be stored. This is done for the training and updation of the model.

## Recognizing an user
Once the user is registered and the model is updated the program will correctly identify the user and display the User ID.

You can always reach out to me [on LinkedIn.](https://www.linkedin.com/in/aditya-khambete-591158170/)

You can also drop a mail [here.](mailto:aditya210699@gmail.com)
