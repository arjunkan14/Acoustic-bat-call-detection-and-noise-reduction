# Acoustic-bat-call-detection-and-noise-reduction
Implementation-python-google-colab-notebook-tensorflow
With time, the interest in recognizing sounds of species that are capable of true flight
has increased. This is important for monitoring our biodiversity and environment health. For
example, bats (which are the only mammals that can fly) play a crucial role in our environment. Bats
use ultrasonic pulse as well as echolocation calls to search for food, communicate to other and
avoiding obstacles. However, manual examination of such sounds is too time-consuming, and hence,
not suitable for mass study. The main challenge lies in tackling the background noises that come
with these calls. To tackle this problem, many applications are being developed in recent years to
automatically detect the vocal sounds of such species, using various machine learning approaches
such as nearest neighbour, decision trees, support vector machine, etc.
In this paper, we concentrate on using a deep learning approach to detect bat sounds using a
number of audio recordings as our data sources, and at the same time, handling the background
noises that are present in these datasets using a noise-reduction technique. We used the concept of
mel-frequency cepstrums (MFCs) for our feature extraction. However, in our case, we initially faced
the issue of imbalanced data which could greatly affect the overall performance of our model. We
tried to address this issue by applying four resampling methods on our training data. To train our
model, we used a simple feed-forward neural network and then evaluated our results with each of
these resampling methods.
