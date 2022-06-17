# SABER-IMC_publication
List of Cellprofiler piplines and R codes used for the analysis of the data used for the paper Hosogane et al., about signal amplification for imaging mass cytometry.

### Signal and background intensity quantification
thresholding_dev1.cppipe:
- Create signal and background region masks by thresholding using CellProfiler.

### Single cell segmentation
calculate_intensity.cppipe:
- Quantification of mean signal and background intensities from region masks (Fig.3, Fig.S2, Fig.S3)


### SABER_preprocessing script
SABER_preprocessing.Rmd :
-  Conversion of single cell data from Cell profiler to SingleCellExperiment object.
-  Data scaling and filtering


### SABER_celltyping scripts
SABER_celltyping.Rmd :
- Single cell phenotyping and expression quantification (Fig.5,S5)
- Visualisation of cell populations and markers (Fig.5,S5)

