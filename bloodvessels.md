
## [Home](/index) / [Brief CV](/brief_cv) / [Research](/research) / [News](/news) / [Contact](/contact)

---

## Visualization and localization of blood vessels in speckle images

### Statement

I thank [Dr. José de Jesús Rangel-Magdaleno](https://scholar.google.es/citations?user=aBNkfEsAAAAJ&hl=es), [Dr. Hayde Peregrina-Barreto](https://scholar.google.es/citations?user=Wh2blp0AAAAJ&hl=es), and [Dr. Julio Cesar Ramirez-San-Juan](https://scholar.google.es/citations?user=xN03bqgAAAAJ&hl=es) for integrating me into the speckle team. Also, as soon as I have authorization and the work is published, I will report the codes of the methods used.

I am currently working on denoising with wavelets, improve quality image, segmenting with traditional and clustering methods such as knn. 



![Visualization and localization of blood vessels in speckle images](/images/bloodvessels.png)



### Research

Our research helps to improve the visualization of blood vessels inside the biological tissue. To achieve this goal we carry out research in biophotonics, high noise signals, digital image processing, and segmentation algorithms. 

In this research we address the use of the Discrete Wavelet Transform (DWT) as a multilevel filtering method and region segmentation techniques to improve visualization and localization in LSI images. 


### Summary

| Work | Dataset |    Methods   | Localization | Visualization | Performance |
|:----:|:-------:|:------------:|:------------:|:-------------:|:-----------:|
|`[1]` | `Set A` | `DWT-SL+MM`  |       ✔️     |       ✔️      |`JI: 52.98%` |
|`[2]` | `Set B` | `DWT-SL+KNN` |       ✔️     |               | `JI: 0.XX`  |
|`[3]` | `Set B` | `KNN`        |       ✔️     |               | `JI: 0.XX`  |
|`[4]` | `Set A` | `DWT-AL+MM`  |       ✔️     |       ✔️      | `JI: 0.XX`  |

*Working in this table.

### Work

1. *Visualization of in-vitro Blood Vessels in Contrast Images Based on Discrete Wavelet Transform Decomposition* [[Paper]](https://ieeexplore.ieee.org/document/8827144) [[Code]](https://github.com/friscolt/i2mtc-2019) [[Poster]](https://www.researchgate.net/publication/333146308_Visualization_of_in-vitro_Blood_Vessels_in_Contrast_Images_Based_on_Discrete_Wavelet_Transform_Decomposition)

2. *Effect of the Exposure Time in Laser Speckle Imaging for Improving Blood Vessels Localization: a Wavelet Approach* [[Paper]](https://ieeexplore.ieee.org/document/9129242/) [[Code]](https://github.com/friscolt/i2mtc-2020) [[Keynote]](https://www.researchgate.net/publication/341626117_Effect_of_the_Exposure_Time_in_Laser_Speckle_Imaging_for_Improving_Blood_Vessels_Localization_a_Wavelet_Approach)

3. *Localization of Blood Vessels in in-vitro LSCI Images with K-Means* [[Paper]](https://github.com/friscolt/i2mtc-2021/blob/main/i2mtc2021.pdf)
[[Code]](https://github.com/friscolt/i2mtc-2021) [[Poster]](https://www.researchgate.net/publication/350372727_Localization_of_Blood_Vessels_in_In-Vitro_LSCI_Images_with_K-Means)

4. *Visualization of Blood Vessels in in-vitro Raw Speckle Images Using an Energy-based Decomposition Criteria on DWT Coefficients*

### Datasets

*  `Set A:` 14 packets of  *in-vitro* raw speckle images (straight (7) and bifurcated (7)) of blood vessels at 0µm to 900µm
*  `Set B:` 90 packets of *in-vitro*  raw speckle images (straight) of blood vessels at 0µm to 1000µm 


### Methods

* `DWT-SL + MM:` Discrete Wavelet Transform of simple level with mathematical morphology 
* `DWT-SL + KNN:` Discrete Wavelet Transform of simple level with K-Nearest Neighbors classifier
* `KNN:` K-Nearest Neighbors classifier
* `DWT-AL + MM:` Discrete Wavelet Transform automatic level with mathematical morphology 

### Performance

* JI: Jaccard Index
