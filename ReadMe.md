# Workflow and Strategies for LC-MS based Qualitative and Quantitative Metabolomics Data Analysis

---

## Quantitative Analysis

### 1. Feature detection

**XCMS Family**

[0] Smith, Colin A., et al. "XCMS: Processing Mass Spectrometry Data for Metabolite Profiling Using Nonlinear Peak Alignment, Matching, and Identification." *Analytical Chemistry* 78.3 (2006): 779-787. [url](https://pubs.acs.org/doi/10.1021/ac051437y) *(XCMS-findPeaks.matchedFilter)*

[1] Tautenhahn, Ralf, Christoph Bottcher, and Steffen Neumann. "Highly sensitive feature detection for high resolution LC/MS." *BMC Bioinformatics* 9.1 (2008): 504-504. [url](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-9-504) *(XCMS-findPeaks.centWave, wavelet-based peak detection)*

[2] Conley CJ, Smith R, Torgrip RJ, Taylor RM, Tautenhahn R and Prince JT "Massifquant: open-source Kalman filter-based XC-MS isotope trace feature detection" Bioinformatics 2014, 30(18):2636-43.[url](https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btu359) *(XCMS-findPeaks.massifquant, Kalman tracer)*

[3] Treutler, Hendrik, and Steffen Neumann. "Prediction, Detection, and Validation of Isotope Clusters in Mass Spectrometry Data." *Metabolites* 6.4 (2016). [url](http://www.mdpi.com/resolver?pii=metabo6040037) *(XCMS-findPeaks.centWaveWithPredictedIsotopeROIs, Isotope clusters)*

**MZMine Family**

[4] Katajamaa, Mikko, Jarkko Miettinen, and Matej Oresic. "MZmine: toolbox for processing and visualization of mass spectrometry based molecular profile data." *Bioinformatics* 22.5 (2006): 634-636.[url](https://academic.oup.com/bioinformatics/article-lookup/doi/10.1093/bioinformatics/btk039)

[5] Pluskal, Tomas, et al. "MZmine 2: Modular framework for processing, visualizing, and analyzing mass spectrometry-based molecular profile data." *BMC Bioinformatics* 11.1 (2010): 395-395. [url](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-11-395)

[6] Trevino, Victor, et al. "GridMass: A fast two-dimensional feature detection method for LC/MS." *Journal of Mass Spectrometry* 50.1 (2015): 165-174.[url](https://onlinelibrary.wiley.com/doi/full/10.1002/jms.3512) *(2D feature detection)*

**OpenMS Family**

[7] Kohlbacher, Oliver, et al. "TOPP---the OpenMS proteomics pipeline." *Bioinformatics* 23.2 (2007): 191-197. [url](https://academic.oup.com/bioinformatics/article/23/2/e191/201948)

[8] Kenar, Erhan, et al. "Automated Label-free Quantification of Metabolites from Liquid Chromatography–Mass Spectrometry Data." *Molecular & Cellular Proteomics* 13.1 (2014): 348-359. [url](https://www.mcponline.org/content/13/1/348) *(OpenMS-FeatureFinderMetabo)*

**Adaptive EIC**

[9] Yu, Tianwei, et al. "apLCMS--adaptive processing of high-resolution LC/MS data.." *Bioinformatics* 25.15 (2009): 1930-1936. [url](https://academic.oup.com/bioinformatics/article/25/15/1930/211035) *(adaptive binning size for EIC)*



### 2. Feature annotation

### 3. Feature grouping

### 4. Normalization

### 5. Missing value imputation

### 6. Integrated Framework



## Qualitative Analysis

### 1. Isotope analysis

### 2. Fragmentation tree

### 3. In-silicon spectrum

### 4. Fingerprint prediction

### 5. Pathway-based method





