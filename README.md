🖼️ Neural Style Transfer using VGG19 and ResNet50

Tech Stack: TensorFlow, Keras, OpenCV, NumPy, Matplotlib
Domain: Deep Learning, Computer Vision

1. Developed a Neural Style Transfer model that blends the content of one image with the style of another using pre-trained CNN architectures (VGG19 and ResNet50). Extracted feature representations from intermediate layers of the models and optimized a target image by minimizing a custom loss function combining content and style differences.

2. Implemented style extraction using Gram matrices from multiple convolutional layers.

3. Used gradient descent to iteratively update image pixels (treated as trainable variables).

4. Applied both VGG19 (original NST model) and ResNet50 to compare stylization quality.

5. Tuned hyperparameters (content/style weights, learning rate, optimizer settings) for high-quality output.

6. Visualized training output and final stylized images using Matplotlib.
