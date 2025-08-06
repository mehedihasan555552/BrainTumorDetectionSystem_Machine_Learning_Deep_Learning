# Brain Tumor Detection System using Machine Learning & Deep Learning

Brain tumors represent a major medical challenge, requiring early detection and accurate classification to improve patient outcomes. The unchecked growth of brain cells in tumors can affect nearby tissues, with symptoms varying based on factors such as tumor location, size, and cellular composition. Distinguishing between cancerous and non-cancerous tumors is essential for determining the appropriate treatment and prognosis.

This research proposes a novel method leveraging **Convolutional Neural Networks (CNN)** with the **U-Net** architecture for effective brain tumor detection from MRI images.

## Methodology

The system utilizes **deep learning** techniques and uses publicly available datasets from:

- **The Cancer Genome Atlas (TCGA)**
- **The Cancer Imaging Archive (TCIA)**

These datasets consist of MRI images from **455 patients**, providing the necessary training and testing data for developing and evaluating the system.

### Proposed Approach:
- **U-Net Architecture**: A deep learning model designed for medical image segmentation, which is ideal for detecting and classifying tumors from MRI images.
- **Convolutional Neural Networks (CNN)**: Used for feature extraction and classification of tumor types from the MRI images.

The experimental results are significant, with the model achieving a **99.83% accuracy** on the dataset, highlighting the effectiveness of the proposed system in accurately detecting brain tumors. 

## Results

The proposed **U-Net** model outperforms existing deep learning techniques for brain tumor detection, as shown in a comparative analysis with other approaches in the literature.

### Key Highlights:
- **Test Accuracy**: The model achieved an impressive **99.83%** accuracy in detecting and classifying brain tumors from MRI images.
- **Deep Learning Advantage**: This technique is highly superior to traditional methods for detecting subtle features in MRI images, enhancing the speed and accuracy of brain tumor diagnosis.

## Applications

The continuous search for improved diagnostic tools in medical imaging emphasizes the potential of deep learning techniques in revolutionizing the analysis and treatment of brain tumors. This research opens up opportunities for further advancements in **medical imaging analysis** and can be applied in the development of automated systems for **medical diagnosis** and **treatment planning**.

## Example Results

### Test Accuracy:
![Test Accuracy](https://github.com/mehedihasan555552/BrainTumorDetectionSystem_Machine_Learning_Deep_Learning/blob/main/accuracy_chart.jpg?raw=true)

### MRI Image with Result:
![Brain MRI with Result](https://github.com/mehedihasan555552/BrainTumorDetectionSystem_Machine_Learning_Deep_Learning/blob/main/brain_mri_image_with_result.jpg?raw=true)

## License

This project is licensed under the **MIT License**.
