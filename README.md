# Concept
Without knowing anything at all about Panda classification, I propose a new way to identify pandas in a picture.

The simple idea is to train a model to identify pandas and then compare pixels for dark and white values.

# State Of The Art (Or What I know of it)
Gaussian noise, when added to a picture, can confuse models when it comes to identifying what is in the picture.
This noise, however, is not seen by the naked eye well. This is why I have thought using a quotient of pixels that
are white and black could be useful in identifying pandas (or other objects) in conjunction with the model as pixels,
as far as I know, are not severely altered by the addition of Gaussian Noise.

# Disclaimer
This is just a thought-child of a late-night rabbit hole. I apologize if I offend someone who knows something about 
this topic and knows it cannot be done. Please let me know, if you so desire.
