#                                  Breast Cancer Detection using VGG16 and Xception with Multihead Attention Mechanism

Breast cancer is a kind of cancer that begins as a growth of cells in the breast tissue.
After skin cancer, breast cancer is the most common cancer diagnosed in women in the United States. But breast cancer doesn't just happen in women. Everyone is born with some breast tissue, so anyone can get breast cancer.
Breast cancer survival rates have been increasing. And the number of people dying of breast cancer is steadily going down. Much of this is due to the widespread support for breast cancer awareness and funding for research.
Advances in breast cancer screening allow healthcare professionals to diagnose breast cancer earlier. Finding the cancer earlier makes it much more likely that the cancer can be cured. Even when breast cancer can't be cured, many treatments exist to extend life. New discoveries in breast cancer research are helping healthcare professionals choose the most effective treatment plans.

### Breast Cancer types:-
Healthcare providers determine cancer types and subtypes so they can tailor treatment to be as effective as possible with the fewest possible side effects. Common types of breast cancer include:
•	Invasive (infiltrating) ductal carcinoma (IDC): This cancer starts in your milk ducts and spreads to nearby breast tissue. It’s the most common type of breast cancer in the United States.
•	Lobular breast cancer: This breast cancer starts in the milk-producing glands (lobules) in your breast and often spreads to nearby breast tissue. It’s the second most common breast cancer in the United States.
•	Ductal carcinoma in situ (DCIS): Like IDC, this breast cancer starts in your milk ducts. The difference is DCIS doesn’t spread beyond your milk ducts.
Less common breast cancer types include:
•	Triple-negative breast cancer (TNBC): This invasive cancer is aggressive and spreads more quickly than other breast cancers. 
•	Inflammatory breast cancer (IBC): This rare, fast-growing cancer looks like a rash on your breast. IBC is rare in the United States.
•	Paget’s disease of the breast: This rare cancer affects the skin of your nipple and may look like a rash. Less than 4% of all breast cancers are Paget’s disease of the breast.

### Breast Cancer subtypes: -
Healthcare providers classify breast cancer subtypes by receptor cell status. Receptors are protein molecules in or on cells’ surfaces. They can attract or attach to certain substances in your blood, including hormones like estrogen and progesterone. Estrogen and progesterone help cancerous cells to grow. Finding out if cancerous cells have estrogen or progesterone receptors helps healthcare providers plan breast cancer treatment.
Subtypes include:
•	ER-positive (ER+) breast cancers have estrogen receptors.
•	PR-positive (PR+) breast cancers have progesterone receptors.
•	HR-positive (HR+) breast cancers have estrogen and progesterone receptors.
•	HR-negative (HR-) breast cancers don’t have estrogen or progesterone receptors.
•	HER2-positive (HER2+) breast cancers, which have higher than normal levels of the HER2 protein. This protein helps cancer cells to grow. About 15% to 20% of all breast cancers are HER2-positive.

### What causes breast cancer?
Experts know breast cancer happens when breast cells mutate and become cancerous cells that divide and multiply to create tumors. They aren’t sure what triggers that change. However, research shows there are several risk factors that may increase your chances of developing breast cancer. These include:
•	Age: Being 55 or older.
•	Sex: Women and people AFAB are much more likely to develop the condition than men and people AMAB.
•	Family history: If your parents, siblings, children or other close relatives have breast cancer, you’re at risk of developing the disease.
•	Genetics: Up to 15% of people with breast cancer develop the disease because they have inherited genetic mutations. The most common genetic mutations involve the BRCA1 and BRCA2 genes. 
•	Smoking: Tobacco use has been linked to many different types of cancer, including breast cancer.
•	Drinking beverages containing alcohol: Research shows that drinking beverages containing alcohol may increase breast cancer risk.
•	Having obesity.
•	Radiation exposure: If you’ve had prior radiation therapy — especially to your head, neck or chest — you’re more likely to develop breast cancer.
•	Hormone replacement therapy: People who use Hormone Replacement Therapy (HRT) have a higher risk of being diagnosed with the condition.

### Diagnosis & Tests: -
Healthcare providers may do physical examinations or order mammograms to check for signs of breast cancer. But they do the following tests to diagnose the disease:
•	Breast ultrasound.
•	Breast Magnetic Resonance Imaging (MRI) scan.
•	Breast biopsy.
•	Immunohistochemistry test to check for hormone receptors. 
•	Genetic tests to identify mutations that cause breast cancer.



#                                                                          PROJECT OVERVIEW

### Dataset: -
The data collected at baseline include Breast ultrasound images among women between 25 and 75 years old. This data was organized in 2018. The number of patients is 600 females, patients. The dataset consists of 780 images with an average image size of 500*500 pixels. The images are in PNG format. The ground truth images are presented with original images. The images are categorized into three classes, which are standard, benign, and malignant.
The project utilized Breast Cancer imaging data in PNG format. The images were processed and classified into three categories for diagnosis.

### Model Used:
•	VGG16 with Attention Mechanism: A well-established CNN (Convolutional Neural Network) architecture known for its performance in image classification tasks.
•	Xception with Attention Mechanism: A more advanced model, incorporating depthwise separable convolutions, aimed at improving Efficiency and Accuracy.

### Methodology: -
•	Applied ImageDataGenerator for Data Preprocessing and Augmentation.
•	Implemented Attention Layers to improve the focus within the images.
•	Evaluated both models based on Precision, Recall & F1-Score.

## Results: -
### 1)	VGG16:  Precision = [0.67, 1.00, 0.88]; Recall = [0.89, 0.57, 0.98]; F1-Score = [0.76, 0.72, 0.92]; Accuracy = 81%
### 2)	Xception: Precision = [0.95, 0.91, 0.94]; Recall = [0.84, 0.95, 1.00]; F1-Score = [0.89, 0.93, 0.97]; Accuracy = 93%

## Conclusion:-
This project showcased the strengths of both VGG16 and Xception for for medical imaging tasks with Xception showing better overall performance. The attention mechanism played overall performance. The attention mechanism played a critical role in boosting model accuracy by focusing on the most important parts of the images.

