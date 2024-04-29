# Image-Captioning-Program
This project builds an image captioning model that will analyse input images and generate a short description.

# Team Members 

<li><a href="https://sharmahemang.com">Hemang Sharma</a></li>

# File and Dataset Description


Flickr8k.token.txt - the raw captions of the Flickr8k Dataset . The first column is the ID of the caption which is "image address # caption number"

Flickr8k.lemma.txt - the lemmatized version of the above captions 

Flickr_8k.trainImages.txt - The training images used in our experiments
Flickr_8k.devImages.txt - The development/validation images used in our experiments
Flickr_8k.testImages.txt - The test images used in our experiments


ExpertAnnotations.txt is the expert judgments.  The first two columns are the image and caption IDs.  Caption IDs are <image file name>#<0-4>.  The next three columns are the expert judgments for that image-caption pair.  Scores range from 1 to 4, with a 1 indicating that the caption does not describe the image at all, a 2 indicating the caption describes minor aspects of the image but does not describe the image, a 3 indicating that the caption almost describes the image with minor mistakes, and a 4 indicating that the caption describes the image.


CrowdFlowerAnnotations.txt contains the CrowdFlower judgments.  The first two columns are the image and caption IDs.  The third column is the percent of Yeses, the fourth column is the total number of Yeses, the fifth column is the total number of Noes.  A Yes means that the caption describes the image (possibly with minor mistakes), while a No means that the caption does not describe the image.  Each image-caption pair has a minimum of three judgments, but some may have more.

# Refrence

<li>M. Hodosh, P. Young and J. Hockenmaier (2013) "Framing Image Description as a Ranking Task: Data, Models and Evaluation Metrics", Journal of Artifical Intellegence Research, Volume 47, pages 853-899
http://www.jair.org/papers/paper3994.html</li>

<li>https://daniel.lasiman.com/post/image-captioning/</li>
<li>https://github.com/sgrvinod/a-PyTorch-Tutorial-to-Image-Captioning</li>
<li>https://towardsdatascience.com/image-captioning-with-keras-teaching-computers-to-describe-pictures-c88a46a311b8</li>
<li>https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/</li>
<li>https://towardsdatascience.com/how-to-build-an-image-captioning-model-in-pytorch-29b9d8fe2f8c</li>

