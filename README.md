# Smart Manufacutring with Convolutional Neural Networks
The dataset comprises 455 labeled images grouped into the categories: Normal, Bubbles, Overextrusion, Overextrusion10, and Overextrusion40. These images span the entire manufacturing process—from initial stages to the final part assembly—and are intended for use in computer vision applications. Each category name reflects a typical extrusion-related defect.

Filename examples:

    Normal_1.png: Final stage image from the “Normal” category
    Normal_88.png: Early-stage image of a normal process
    Overextrusion_2.png: Late-stage image showing overextrusion
    Overextrusion40_80.png: Early-stage image from the “Overextrusion40” set


![image](https://github.com/user-attachments/assets/9dc509d6-e590-4c1a-bef3-f04631f26efe)

Industry 4.0 marks a shift toward intelligent manufacturing, where real-time monitoring and automation are key. This project focuses on classifying quality defects in 3D-printed parts accross five classes, namely normal, overextrusion, overextrusion10, overextrusion40, bubbles using Convolutional Neural Networks (CNNs).
By analyzing images of printed layers, the model detects and categorizes defects, enabling faster and more reliable quality control. This approach supports the development of smarter, automated systems in additive manufacturing.

Multiple Convolutional Neural Networks were employed in the project:

    🧩 Simple CNN – A custom-built baseline architecture

    ⚡ EfficientNetB0V2 – A modern, lightweight yet powerful CNN

    🏗️ ResNet – A deep residual network for robust feature extraction

The models analyze printed layer images to classify defects, enabling faster, automated quality inspection in additive manufacturing workflows.






📈 Experimental Results

The models were trained and evaluated on labeled images of 3D-printed parts to classify common defects. Below is a summary visualization of the performance metrics and training behavior.

![image](https://github.com/user-attachments/assets/a34aa4bb-6714-4741-8d5e-a3ead09e5ad6)




