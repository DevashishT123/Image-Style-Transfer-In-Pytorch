# Image-Style-Transfer-In-Pytorch
Combine two images and produce new image with style of first image and content of second image

# About Project:

"The primary objective of this project is to blend two images, yielding a novel composite image. This fusion process operates uniquely, where we merge the artistic style of one image with the content of another. Typically, we designate one image as the 'content image' and the other as the 'style image,' aligning with the approach outlined in the referenced research paper.

Convolutional Neural Networks (CNNs) are pivotal in image classification and recognition tasks. Within this project, we leverage the VGG19 architecture, a CNN variant. The initial layers of VGG19 capture fundamental features and shapes, while deeper layers discern more intricate image patterns. Consequently, we extract content from the latter layers of the CNN. For style extraction, we employ the Gram Matrix to analyze correlations across different layers.

The initial step involves selecting a target image, often initialized with random noise (though using the content image as a starting point is beneficial). By computing Content and Style losses and iteratively minimizing these losses, we converge towards an optimal target image that seamlessly combines the style of one image with the content of another.

Please note that the provided notebook is designed for use in Google Colab. When adapting this code for local execution, you may disregard the first four cells. To create new styled images, modify the links assigned to the style and content variables, adjust the file path in the final cell, specify the location to save the styled image, and then execute the entire notebook."
