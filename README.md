# ml_synth

![ml_symth](https://user-images.githubusercontent.com/33290161/170257547-4c65a5df-0e6e-4845-8e15-1c77ac61c4a0.png)


## Education tool to introduce Machine Learning concepts through sound synthesis

By Joaquín Jiménez-Sauma 
<br />[jjsauma.com](http://jjsauma.com/) 

This patch lets you design sounds using the top left dials, while classifying and saving them as part of your machine learning model. 

To produce sounds, press the "Q" letter on your keyboard.

The patch starts untrained. Once you configured a sound you want to use as training (by setting dial controls at the top), switch to Train mode. Write three semantic levels you want to use to describe the sound in the green textboxes above the knobs. You should keep these categories all the time. Set the three dial values to the ones you think represent the sound and press "Add this state to training". Continue creating different sounds, classifying them and adding them to training. 

Once you have a good number of examples (above 10 is a good number), you can switch to Play mode and set the semantic categories to the levels you want and you will be able to hear the predicted sounds while pressing "Q".

This patch uses ML.* (ml.star) Max/MSP package by Benjamin D. Smith, which you should install to make this patch work.

Suggestion or improvements or want to contribute? Please let me know.
