Problem Statement
**Context**

**Part A:**

A communications equipment manufacturing company has a product that is responsible for emitting informative signals. The company wants to build a machine learning model that can help the company predict the equipment’s signal quality using various parameters.

**Part B:**

Recognizing multi-digit numbers in photographs captured at street level is an important component of modern-day map making. A classic example of a corpus of such street-level photographs is Google’s Street View imagery composed of hundreds of millions of geo-located 360-degree panoramic images.

The ability to automatically transcribe an address number from a geo-located patch of pixels and associate the transcribed number with a known street address helps pinpoint, with a high degree of accuracy, the location of the building it represents.

More broadly, recognizing numbers in photographs is a problem of interest to the optical character recognition community.

While OCR on constrained domains like document processing is well studied, arbitrary multi-character text recognition in photographs is still highly challenging. This difficulty arises due to the wide variability in the visual appearance of text in the wild on account of a large range of fonts, colors, styles, orientations, and character arrangements.

The recognition problem is further complicated by environmental factors such as lighting, shadows, specularity, and occlusions as well as by image acquisition factors such as resolution, motion, and focus blurs.

In this project, we will use the dataset with images centered around a single digit (many of the images do contain some distractors at the sides). Although we are taking a sample of the data which is simpler, it is more complex than MNIST because of the distractor.

**Objective**
Part A: To build a classifier that can use the given parameters to determine the signal strength or quality.

Part B: To build a digit classifier on the SVHN (Street View Housing Number) dataset. Do the users spend more time on the new landing page than on the existing

**Data Dictionary**
**Part A**

Parameters: Various measurable signal parameters.
Signal_Quality: Final signal strength or quality.
**Part B**

The SVHN is a real-world image dataset for developing machine learning and object recognition algorithms with the minimal requirement on data formatting but comes from a significantly harder, unsolved, real-world problem (recognizing digits and numbers in natural scene images). SVHN is obtained from house numbers in Google Street View images.

Where the labels for each of these images are the prominent number in that image, i.e., 2, 6, 7, and 4, respectively. The dataset has been provided in the form of h5py files.
