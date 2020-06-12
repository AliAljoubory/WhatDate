# WhatDate

WhatDate, as its name implies, is a date app that was created using my own model with the Create ML framework, used to check the type of date you have inputed as an image.

WhatDate allows you to pass in an image from your library or right from your camera, before doing its magic. Upon analysis, it spits out the variety of date it believes you have inputed using a typical UIAlertController.

Of course WhatDate focused less on the app interface and much more on the trained Create ML model. I fed it upwards of 100 images each for 2 varieties of dates to start off with, Bahri and Sukkari.

Around 20% of those images were used for testing data and the remaining 80% for training. On most days it’s accuracy is pretty spot on, however it does have those times where even a clear image would cause it problems, pointing towards the model requiring more expanded training.
