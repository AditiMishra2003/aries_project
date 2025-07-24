🖼️ Neural Style Transfer using VGG19 and ResNet50
Tech Stack: TensorFlow, Keras, OpenCV, NumPy, Matplotlib
Domain: Deep Learning, Computer Vision

Developed a Neural Style Transfer model that blends the content of one image with the style of another using pre-trained CNN architectures (VGG19 and ResNet50). Extracted feature representations from intermediate layers of the models and optimized a target image by minimizing a custom loss function combining content and style differences.

Implemented style extraction using Gram matrices from multiple convolutional layers.

Used gradient descent to iteratively update image pixels (treated as trainable variables).

Applied both VGG19 (original NST model) and ResNet50 to compare stylization quality.

Tuned hyperparameters (content/style weights, learning rate, optimizer settings) for high-quality output.

Visualized training output and final stylized images using Matplotlib.
