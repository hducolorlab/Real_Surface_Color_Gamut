# Real Surface Color Gamut

## 📌 1. Overview  
This dataset contains 102,801 reflectance samples constituting the gamut of real surface colors under D65 illuminant in CIELAB color space. The proposed gamut serves as a reference for:

- Gamut mapping in color reproduction workflows    

- Display device gamut evaluation 
---

## 🗃 2. Dataset Composition  
The gamut of real surface colours is constituted of both natural and artificial colours. The category of natural colours includes, but is not limited to, vegetables and grass. The category of artificial colours encompasses textiles, plastics, coatings and others.

### **Data Sources**  
- **Core Data**: 85,789 spectra from Li et al. [1] (University of Leeds + ISO TR 16066)  
- **Supplements**:  
  - 11,563 spectra[2]-[5]  

##  **3.File Description**  
| File                     | Description                          | Format     |  
|--------------------------|--------------------------------------|------------|  
| `Proposed_Gamut_D65.csv` | Proposed colour gamut for representing real surface colours       | csv      |  
| `Full_Gamut_D65.csv` | Full colour gamut that fully contain the dataset of real surface colours , with a slightly larger volume, provided as supplementary material.       | csv       |  

## Reference
1.	Li, Changjun, et al. "Comparison of real colour gamuts using a new reflectance database." Colour Research & Application 39.5 (2014): 442-451.
2.	Park, J. and K.M. Park. Professional colour communicator (PCC) - the definitive colour selector. Book of Papers - Aatcc 1994 International Conference & Exhibition, 1994, pp.294-296.
3.	Jones, Michael J., and James M. Rehg. "Statistical colour models with application to skin detection." International journal of computer vision 46 (2002): 81-96.
4.	Sun, Qun, and Mark D. Fairchild. "Statistical characterization of face spectral reflectances and its application to human portraiture spectral estimation." Journal of Imaging Science and Technology 46.6 (2002): 498-506.
5.	Sun, Q. and M. Fairchild. A new procedure for capturing spectral images of human portraiture. Proceedings of the 9th Congress of the International Colour Association, AIC Color 2001, 2001.
