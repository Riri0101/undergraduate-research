# Undergraduate Research

Deep learning research from my undergraduate studies in Computer Engineering at NMIMS University, Mumbai.

---

## Bridging Art and Fashion: AI-Driven Techniques for Seamless Design Integration

🎤 Presented at the International Conference on AI and ML (ICAML), Aug 2024

📄 [Read the paper](art-fashion-design-integration-paper.pdf)

**Problem:** Applying artwork to clothing is still largely manual, slow and wasteful, and existing style transfer models often ignore the garment's texture and shape.

**Approach:** Combined two deep learning models to place artwork onto T-shirts realistically. ResNet18 extracts the T-shirt's structure and fabric texture so the garment keeps its shape, and Pix2Pix (a GAN for image-to-image translation) maps the artwork onto it. Trained on a dataset of 8,683 artwork images.

**Result:** Pix2Pix reached an MSE of 0.0486 with an inference time of about 0.007 seconds per image, while ResNet18 preserved garment structure with an SSIM of 0.9185. Together, they produced realistic designs in seconds, supporting faster digital prototyping with less material waste.

**Co-author:** Prof. Sofia Francis

---

## From Pixels to Pronunciation: A Deep Learning System for Image Description and Speech Generation

📄 [Read the paper](https://github.com/Riri0101/undergraduate-research/blob/main/From%20Pixels%20to%20Pronunciation.pdf)

**Problem:** Elderly and visually impaired people often can't independently access visual content.

**Approach:** Built an image-to-speech system that describes images out loud. InceptionV3 extracts image features, an attention mechanism focuses on the most relevant parts of the image, and a GRU decoder generates a caption that is converted to speech. Trained on the Flickr8k dataset (8,000 images, about 40,000 captions).

**Result:** 91.4% accuracy, with CIDEr and METEOR scores improving steadily across training. Works best on simpler scenes; complex scenes and longer captions remain a challenge.

**Co-authors:** Mehek Wagle, Prof. Avani Bhuva

---

## A Deep Learning Approach to Fabric Defect Detection: CNN and ResNet for Efficient Quality Assessment

📄 [Read the paper](https://github.com/Riri0101/undergraduate-research/blob/main/A%20Deep%20Learning%20Approach%20to%20Fabric%20Defect%20Detection_%20CNN%20and%20ResNet%20for%20Efficient%20Quality%20Assessment.pdf)

**Problem:** Manual fabric inspection in the textile industry is slow, costly and prone to human error.

**Approach:** Compared a custom CNN and a pretrained ResNet (transfer learning) for classifying fabric images into six classes: good, color, cut, hole, thread and metal contamination. Used 48,000 labeled images with augmentation (rotation, flipping, cropping).

**Result:** The CNN reached 76% accuracy and ResNet reached 72%. The simpler CNN performed better on the small 32x32 images, a useful lesson in matching model complexity to the data.

**Co-authors:** Mehek Wagle, Tarushi Marchino, Sofia Francis, Dr. Soni Sweta

---

*The first paper was presented at ICAML 2024. The other two were completed as part of my undergraduate practicum and have not been published.*
