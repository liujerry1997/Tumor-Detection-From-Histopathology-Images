# Tumor-Detection-From-Histopathology-Images

Our project falls under the category of histopathology, which is the field of diagnosing and studying diseases by examining tissues and cells via microscopy. A clinically-relevant and important problem in this field is the ability to identify and classify cancer based on digital pathology scans of the tissue. For example, here are two lymph tissue section images, one from tumorous tissue and the other from healthy tissue. Traditionally, this would be done manually by trained experts in the field, which would cost a lot of time and effort. Fortunately, as machine learning developed and evolved, we can design algorithms and models to analyze and classify images for us, speeding up the process, saving resources, and increasing accessibility to histopathologic expertise. 

The objective of our model is to be able to classify a specific region in a tissue image as cancerous or healthy. In this case, given a 96x96 pixel image, we will focus on the center 32x32 pixel region and label the image based on if there is at least a single pixel of tumor tissue within this region. This means that any tumor tissues outside of the region should play no role in the labeling process.

The result and model are discussed in detail in the presentation slides.
