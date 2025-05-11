Cross-View Dynamic Learning-Based Multi-Class Industrial Anomaly Detection

This research paper is in the submission stage. If accepted, I plan to open-source the entire project—including code, datasets, and documentation—to support reproducibility and community collaboration. This initiative aims to make our findings and tools accessible to all researchers and practitioners.


Dataset： Real-IAD： A new large-scale challenging industrial AD dataset, containing 30 classes with totally 151,050 images; 2,000 ∼ 5,000 resolution; 0.01% ~ 6.75% defect proportions; 1:1 ~ 1:10 defect ratio. Download and extract Real-IAD into data/realiad. ：https://realiad4ad.github.io/Real-IAD/


MVTec-AD consists of 15 object categories, including 5 texture classes and 10 object classes, with a total of 5,354 high-resolution images.


VisA  contains 10,821 high-resolution images across 12 objects with complex structures, including 9,621 normal images and 1,200 anomaly images. 



Evaluation Metrics： Both image-level and pixel-level met-rics are typically used to evaluate algorithm performance in USDD. Image-level metrics assess whether an entire product is anomalous, while pixel-level metrics measure defect localization and can further evaluate defect severity. Based on previous defect detection work, seven evaluation metrics are employed. Image-level performance is evaluated using Area Under the Receiver Operator Curve (AUROC), Average Precision (AP), and F1 score at the optimal threshold (F-max). Pixel-level performance is measured by AUROC, AP, F-max, and the Area Under the Per Region Overlap (AUPRO). To provide a comprehensive assessment of the model’s perfor-mance, we compute the average of the all-evaluation metrics mentioned above, referred to as mAD. The final dataset result is calculated as the average across all classes.
