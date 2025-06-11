# 🏭 Smart Manufacturing with Convolutional Neural Networks

**Industry 4.0** represents a pivotal shift toward intelligent, automated production systems. In this context, quality assurance becomes increasingly data-driven.
This project leverages **Convolutional Neural Networks (CNNs)** to classify visual defects in 3D-printed parts across five categories:

* **Normal**
* **Bubbles**
* **Overextrusion**
* **Overextrusion10**
* **Overextrusion40**

By analyzing layer-by-layer images from different stages of the manufacturing process, the models support **real-time, automated quality inspection**—a key enabler for smart, scalable additive manufacturing.

---

### 🖼️ Dataset Overview

The dataset consists of **455 labeled images** captured throughout the full printing process—from early layers to final assemblies. Each filename reflects its defect class and stage in the process.

**Examples:**

* `Normal_1.png`: Final-stage image of a defect-free print
* `Normal_88.png`: Early-stage image of a defect-free print
* `Overextrusion_2.png`: Late-stage overextrusion issue
* `Overextrusion40_80.png`: Early-stage image from the Overextrusion40 class

![Dataset Sample](https://github.com/user-attachments/assets/9dc509d6-e590-4c1a-bef3-f04631f26efe)

📦 **Download the dataset**:
🔗 [Full Extruded Dataset on Kaggle](https://www.kaggle.com/datasets/marcelobatalhah/full-extruded-dataset)

---

### 🧠 Models Used

Three CNN architectures were developed and tested to evaluate their effectiveness in detecting extrusion-related defects:

* 🧩 **Simple CNN** – A custom lightweight baseline
* ⚡ **EfficientNetB0V2** – A modern, efficient CNN with strong performance
* 🏗️ **ResNet** – A deep residual network known for robust feature extraction

Each model processes image data to identify defect patterns, improving the speed and accuracy of defect detection.

---

### 📈 Experimental Results

Below is a training summary illustrating performance across the tested CNN architectures.

![Training Results](https://github.com/user-attachments/assets/a34aa4bb-6714-4741-8d5e-a3ead09e5ad6)

---

Let me know if you'd like to add performance metrics in table form, a confusion matrix, or TensorBoard logs in the README.





