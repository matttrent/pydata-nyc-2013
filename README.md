pydata-nyc-2013
===============

Sample iPython notebooks for Image Features in Python talk

In order to run the bag of words notebook, you need the images.  The zip file of them is [available here][].

[available here]: https://dl.dropboxusercontent.com/u/367147/photos.zip

Place the zipfile in this directory, unzip and you're good to go.

The slides for the presentation are available on [Speaker Deck][].

[Speaker Deck]: https://speakerdeck.com/matttrent/image-features-in-python

The video for the talk is available on [Vimeo][].

[Vimeo]:    https://vimeo.com/79536175

Abstract
--------

An increasing amount of information is being conveyed via images, with mobile photographs being a particularly notable case. While image metadata, such as the text linking to an image in Google image search, is a common input to machine learning tasks, the content of the image itself is used far less frequently. Whether picking your best vacation photos, recommending similar-looking images to use in a talk or searching for hidden cats, learning tasks can do better if the actual pixels are used as input.

However, The choice of features determines the quality of result as much as the choice of machine learning algorithm and using the pixels directly often yields the poor results. Higher-level image features, such as face detection, histograms and color statistics like hue binning, provide significantly better performance. While advantageous, these features force the developer to choose from a vast number to accurately capture the details of their problem domain, a challenging task. This talk covers classes of simple image features and how to employ them in machine learning algorithms and focuses on providing basic domain knowledge in imaging/computer vision to developers already familiar with machine learning.

The outline is as follows: We begin with an overview of common image features and discuss potential applications for each. Common features include examples from computer vision such as blob identification, face detection and edge statistics as well as from image statistics such as intensity histograms, Fourier properties and color statistics such as hue binning. Next, we present how to generate the features with python imaging libraries. Finally, we discuss approaches to converting complex image features into a series of scalars for the input vector of an ML algorithm that best represent the problem domain.