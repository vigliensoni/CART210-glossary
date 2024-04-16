Image recognition that takes various images as raw data has wide applications such as medical image diagnosis, optical character recognition, signature authentication, fingerprint identification, iris recognition, DNA sequence identification, image retrieval, visual object detection, face and gesture recognition, autonomous vehicles, military applications, and much more.

The general structure of an image recognition system is composed of four building blocks:

**1-	 Image acquisition**
Image acquisition converts a scene into an array of numbers that can be manipulated by a computer.

**2-	 Image preprocessing and segmentation**
This block removes noise, enhances the picture, and segments the regions of interest from the image background as well as normalizes the segmented sub-image such as rotation, translation, scale and contrast normalization. Both input and output of this building block are images.

**3-	 Feature extraction**
This block reduces the data dimension by removing redundancy and unreliable components from the data and hence represents the object of interest by a reduced set of numerical features.

**4-	Classification**
Classification is the last stage of an image recognition system, where a class label is assigned to the unknown image object by comparing the extracted features with class representations that the classifier has learned during its training stage.

Among the four building blocks of a general image recognition system, feature extraction and classification are more closely related to the pattern recognition discipline than the other two and hence are intensively studied in the research fields of pattern recognition and computer vision.

The goal of feature extraction is to yield a pattern representation that makes the classification trivial. Conversely, a good classification design would not need the help of a sophisticated feature extraction. In fact, there is no conceptually clear boundary between feature extraction and classification.[^general01image_recognition]

## Applications of deep learning in  image recognition

Image recognition technology has appeared in the 1940s, but limited by the technical environment and hardware facilities at that time, at that time did not get a long development. Until the 1990s, artificial neural networks were combined with support vector machines to provide support for the development of image recognition techniques, enabling its wide utilization, for example, in license plate recognition, face recognition, object detection, and so on. However, traditional image recognition techniques use structural models that are insufficient to pre-process images and require manual pre-processing first, leading to reduced accuracy of image recognition. The purpose of deep learning is to extract higher-dimensional and more abstract information by constructing a multilayer network on which the computer automatically learns and obtains the relationships implied by the data internally so that the learned features are more expressive.

**Deep learning**

Deep learning is a branch in machine learning, and its concept is derived from artificial neural networks (ANN), which simulate the pattern of passing and processing information between neurons in the human brain from the perspective of information processing. 

Supervised learning and unsupervised learning are the two main categories of deep learning, and classification is based on whether the data contains markers or not. The supervised learning process identifies the mapping relationship between the features of the training data and the markers, and continuously corrects the bias in the learning process through the markers to continuously improve the prediction rate of learning. 

Deep learning is used in many applications because of its strong ability to extract image features, accurate recognition, and fast real-time.. Especially, it has achieved notable results in face recognition, medical image recognition, remote sensing image recognition, etc. Before the emergence of deep learning technology, image recognition mainly relied on traditional technical means to achieve, for example, principal component analysis (PCA), Laplace feature map method, local value-preserving mapping (LPP), sparse representation, neural network dimensionality reduction, et. However, the image recognition performance is not ideal due to the defects of traditional technical means. Advances in deep learning technology have allowed researchers to gradually apply deep learning to image recognition, and good results have been achieved in subsequent scientific work, and the recognition efficiency and recognition effect of images have improved significantly over traditional recognition means.

**CNN**

Convolutional Neural Network (CNN) is not only an important part of deep learning, but also one of the more widely used models in the field of image recognition. The advantage of the CNN model mainly lies in avoiding a large amount of feature extraction work in the pre-processing of images and simplifying the steps of image pre-processing.

The CNN model is based on the assumption of local correlation and feature repetition of the image, i.e., it is assumed that the pixel at a certain point of the image is generally more correlated with its neighboring pixels and less correlated with other pixels, avoiding the large number of parameters necessary for full connectivity, which is the local connectivity property of CNN.[^deep_learning02image_recognition]

## Pattern recognition and image processing

During the past twenty years, there has been a considerable growth of interest in problems of pattern recognition and image processing. This interest has created an increasing need for theoretical methods and experimental software and hardware for use in the design of pattern recognition and image processing systems.

Although pattern recognition and image processing have developed as two separate disciplines, they are very closely related. The area of image processing consists not only of coding, filtering, enhancement, and restoration, but also analysis and recognition of images. On the other hand, the area of pattern recognition includes not only feature extraction and classification, but also preprocessing and description of patterns. It is true that image processing appears to consider only two-dimensional pictorial patterns and pattern recognition deals with one-dimensional, two-dimensional, and three-dimensional patterns in general. However, in many cases, information about one-dimensional and three-dimensional patterns is easily expressed as two-dimensional pictures, so that they are actually treated as pictorial patterns. Furthermore, many of the basic techniques used for pattern recognition and image processing are very similar in nature. Differences between the two disciplines do exist, but we also see an increasing overlap in interest and a sharing of methodologies between them in the future.

Pattern recognition is concerned primarily with the description and classification of measurements taken from physical or mental processes.

In order to determine a good set of characteristic measurements and their relations for the representation of patterns so good recognition performance can be expected, a careful analysis of the patterns under study is necessary. Knowledge about the statistical and structural characteristics of patterns should be fully utilized. From this point of view, the study of pattern recognition includes both the analysis of pattern characteristics and the design of recognition systems.

The many different mathematical techniques used to solve pattern recognition problems may be grouped into two general approaches:

1-	Decision-theoretic (or discriminant) approach 
In the decision-theoretic approach, a set of characteristic measurements, called features, are extracted from the patterns. Each pattern is represented by a feature vector, and the recognition of each pattern is usually made by partitioning the feature space.
2-	 Syntactic (or structural) approach
The syntactic approach, each pattern is expressed as a composition of its components, called sub patterns or pattern primitives. This approach draws an analogy between the structure of patterns and the syntax of a language.

The recognition of each pattern is usually made by parsing the pattern structure according to a given set of syntax rules. In some applications, both of these approaches may be used. For example, in a problem dealing with complex pattems, the decision-theoretic approach is usually effective in the recognition of pattern primitives, and the syntactic approach is then used for the recognition of sub patterns and of the pattern itself.[^pattern03image_recognition]



[^general01image_recognition]:Jiang, Xudong. 2009. _‘Feature Extraction for Image Recognition and Computer Vision’_. In 2009 2nd IEEE International Conference on Computer Science and Information Technology, 1–15. https://doi.org/10.1109/ICCSIT.2009.5235014.

[^deep_learning02image_recognition]:Li, Yinglong. 2022. _‘Research and Application of Deep Learning in Image Recognition’_. In 2022 IEEE 2nd International Conference on Power, Electronics and Computer Applications (ICPECA), 994–99. https://doi.org/10.1109/ICPECA53709.2022.9718847.

[^pattern03image_recognition]:
Fu, King-Sun and Rosenfeld. 1976. _‘Pattern Recognition and Image Processing’_. IEEE Transactions on Computers C–25 (12): 1336–46. https://doi.org/10.1109/TC.1976.1674602.

