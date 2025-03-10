# **Introduction**

In this project, we explore the use of hyperspectral imaging (HSI) for the analysis of Esther's scroll, a historical document of significant cultural and historical importance.

Hyperspectral imaging, a non-invasive imaging technique, captures detailed spectral information across hundreds of bands, enabling the detection and analysis of subtle features invisible to the human eye [1].

Our approach involves applying various detection algorithms to identify and analyze features of interest within the hyperspectral data. Specifically, we utilize the following target detection methods:

*  ACE (Adaptive Cosine Estimator): Measures the cosine similarity between a pixel and the target spectrum, normalized by the background covariance.

*   Signed ACE:
A variation of ACE that incorporates the sign of the cosine similarity to improve detection performance.

*   Matched Filter (MF):
Enhances the target signal while suppressing background interference, maximizing the signal-to-noise ratio for the target.

*   CEM (Constrained Energy Minimization):
Minimizes the background energy while preserving the target's signature for effective background suppression.


To further enhance these algorithms, we will evaluate the performance using different types of background suppression matrices:


*  Covariance Matrix:
Captures the variance and covariance between spectral bands, effectively modeling the spectral relationships in the data.
*   Correlation Matrix:
A normalized version of the covariance matrix that accounts for the scaling of spectral bands.

In addition to these target detection methods, we also employed Principal Component Analysis (PCA) and False Coloring techniques to enhance the readability of the scroll.


Our goal is to evaluate the effectiveness of these algorithms and matrices in analyzing and interpreting Esther's scroll. By leveraging hyperspectral imaging, we aim to uncover hidden details, detect spectral anomalies, and enhance our understanding of this historical artifact.


![image](https://github.com/user-attachments/assets/f0c2d34f-afcb-4257-9f92-7a0be72cdf92)

Figure 1: Example of Hyperspectral Cube

The Multispectral Imaging System for Historical Artifacts (MISHA), created at the Rochester Institute of Technology (RIT), is an affordable and portable tool for studying historical artifacts. Costing under $10,000, MISHA is a budget-friendly alternative to expensive imaging systems like AVIRIS and MegaVision.

MISHA uses 16 LED lights that shine on an object at different wavelengths, from ultraviolet to near-infrared. Each light creates a grayscale image, and together these images form a detailed "data cube" that helps researchers study the artifact​

One important use of MISHA was to examine an 8th-century Hebrew scroll from RIT's Cary Graphic Arts Collection. The scroll, containing the Book of Esther, had worn sections that were difficult to see. MISHA helped uncover faded text and illustrations, providing new insights into the artifacts.

This project shows how MISHA makes advanced imaging more accessible, enabling smaller institutions to study and preserve their collections. All this information was gathered from [1].
