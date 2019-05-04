# Computer_Vision_Face-Detection
This repo illustrates the implementation of Haar Cascade features to detect face and eyes of a given image of face

The Haar Classifier is a machine learning based approach, an algorithm created by Paul Viola and Michael Jones; which are trained from many many positive images (with faces) and negatives images (without faces).

The Viola-Jones algorithm recognizes that (the majority of) humans have similar properties (called Haar Features).

Some of these properties are that the eye region is darker than upper cheeks and that the eye area is darker than the nose bridge region. Additionally, the algorithm recognizes that the way that most humans faces are constructed is generally the same (the eyes, bridge of the nose, and mouth are almost always in the same place in relation to each other).

OpenCV Library is used to implement Haar Cascade Classifier.

You can learn more about Haar features at https://en.wikipedia.org/wiki/Haar-like_feature
