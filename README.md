# Program-Technologies-Internship-casino-ML

This is a project I worked on while doing internship at Program Technologies. The general task was to create a Chrome extension that would assist user in playing blackjack card game.

My tasks included gathering dataset, prepairing it using Roboflow and using it to train neural network.

First version of dataset consisted of screenshots of various online card gaming web-pages. On this dataset I trained Yolo model. It worked alright on several types of screenshots. Results can be viewed in "results" folder.

However, it was then decided that even tiny version of Yolov4 is too big for Chrome extension, so team decided to go with a smaller model written using Keras. In addition to that dataset was changed to contain only screenshots from one specific web-page. Images then were processed using script in "Processing" notebook. Cut out and filled images containing cards were then used to train Keras model. Keras model and its results can be found in "Keras" notebook.

Later on, I also tested Yolo model on cut out cards and it seemed to work pretty well.
