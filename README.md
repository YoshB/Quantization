# Quantization
The use of the quantization for images

Quantization is a method to reduce the quantity of information in a signal.
For an image this means that we reduce the values of the pixels to a few possible colors instead of
thousands of differents shades of the same color. For example, in an image we can have sky blue, blue king, turquoise
and many others, but the quantization makes that all those colors become in one shade of blue (or the number of shades that we decide), 
thats how we reduce information.

Why is this usefull? 
Because if we want to train a machine learning model is easier for it to find patterns if we have 5 different possible values in the input 
than having 10,000 possible values (this number represents the possible combinations of colors in each pixel).
