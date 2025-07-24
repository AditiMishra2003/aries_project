# 🎨 Neural Style Transfer with VGG19 and ResNet50

This project demonstrates **Neural Style Transfer (NST)** using **TensorFlow** and pre-trained models (**VGG19** and **ResNet50**). The goal is to generate a new image that retains the **content of one image** while adopting the **artistic style of another**.

---

## 📌 Project Highlights

- 🔍 Implemented NST by extracting content and style representations using CNNs.
- 🧠 Used **VGG19** and **ResNet50** as feature extractors (without top layers).
- 🧾 Style captured using **Gram matrices** from intermediate layers.
- 📉 Designed a **custom loss function** that combines content loss and style loss.
- 🔄 Trained the generated image via **gradient descent** for image optimization.
- 🎯 Compared outputs from both models and tuned weights for best visual results.

---

## 🛠️ Tech Stack

- **Python 3**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy**
- **Matplotlib**

---


---

## 🖼️ Sample Images Used

- **Content Image**: ![Dog Image](https://storage.googleapis.com/download.tensorflow.org/example_images/YellowLabradorLooking_new.jpg)
- **Style Image**: ![Kandinsky Style](https://storage.googleapis.com/download.tensorflow.org/example_images/Vassily_Kandinsky%2C_1913_-_Composition_7.jpg)

---

## 🚀 How to Run

1. Clone this repo or download the notebook:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
2. Install dependencies:
    ```bash
    pip install tensorflow matplotlib opencv-python
    ```
3. Open `aries_project.ipynb` in Jupyter Notebook or Google Colab.
4. Run all cells to generate stylized images using both models.

---

## 🧪 Output Example

> Stylized output combining dog content with Kandinsky style:

| 📷 Content Image | 🖌️ Style Image | 🎨 Stylized Output |
|------------------|----------------|--------------------|
| ![content](https://storage.googleapis.com/download.tensorflow.org/example_images/YellowLabradorLooking_new.jpg) | ![style](https://storage.googleapis.com/download.tensorflow.org/example_images/Vassily_Kandinsky%2C_1913_-_Composition_7.jpg) | ✅ Output shown in notebook |

---

## 📊 Experiments

| Feature           | VGG19                         | ResNet50                      |
|------------------|-------------------------------|-------------------------------|
| Content Layer     | `block4_conv2`                | `conv4_block6_out`            |
| Style Layers      | 5 convolutional blocks         | 5 residual blocks             |
| Epochs            | 1000                          | 2000                          |
| Output Comparison | Classic, smoother texture      | Sharper, block-based styling  |

---

## 💡 Future Enhancements

- Upload custom images via UI (e.g., **Streamlit** or **Gradio**)
- Apply NST to real-time webcam feed or video
- Allow layer selection dynamically via dropdown
- Export stylized images in high resolution






