# Mathematics behind Supposrt Vector Machines (SVM)

Supposrt vector machine is one of the basic (binary) classifiers in machine learning based on supervised algorithms. One of the considerable challenges to use this classifier is to know the mathematics behind the algorithm. I believe that the only way to correctly use such algorithms is to know what they mathematically mean and how changes in small parameters may affect the whole process.

In machine learning the data are considered to have bundles of features, and mathematically each one of the features can be indicated by a value on an ax in the coordinate system. For instance, in a very simple case, imagine our classification problem is about to verify similarity between individuals based on their weight and their height. And then, the features of a person like "Tom" can be indicated as a vector of properties (weight= 80 kg, height= 180 cm). Therefore in many of such cases we deal with notion of vectors (in our simple example it is a two dimensional vector while it can be 3 dimensional and more in more complicated scenarios). This is why it is important to have some background on Algebra on working with vectors.

## Some notions from Algebra

Consider a vector ```x``` we refer to its length as **norm** and is computer as below:

![formula](http://www.sciweavers.org/upload/Tex2Img_1612697626/render.png)
