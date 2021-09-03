### Fog Detection in Images

The final result were- train-set acc. = 96.12% and test-set acc. = 82.35%.
In this implementation I have used only the synthetic dataset - http://perso.lcpc.fr/tarel.jean-philippe/bdd/frida.html called FRIDA and FRIDA-2.
The original paper mentions 156-foggy and 156-non foggy images, but here I could only find 84-non foggy images. Thus, I made a balanced dataset of just 169 total images taken from both FRIDA and FRIDA-2 datasets. Therefore the results show less accuracy due to usage of only half of the dataset. However, the feature extraction technique is proper.

Please cite this paper if you use this code for any work -
**Asery, R., Sunkaria, R. K., Sharma, L. D., & Kumar, A. (2016). Fog detection using GLCM based features and SVM. 2016 Conference on Advances in Signal Processing (CASP). doi:10.1109/casp.2016.7746140**

