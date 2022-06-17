# SABER-IMC_publication
List of Cellprofiler piplines and R codes used for the analysis of single cell data in the paper Hosogane et al., about signal amplification for imaging mass cytometry.

### Signal and background intensity quantification
thresholding_dev1.cppipe:
- Create signal region masks and background region masks by thresholding using CellProfiler.

### Single cell segmentation
calculate_intensity.cppipe:
- quantify mean signal and background intensity from the created region masks.


### SABER_preprocessing script

SABER_preprocessing.Rmd :
-  Conversion of single cell data from Cell profiler to SingleCellExperiment object.
-  Data scaling and filtering


### SABER_celltyping scripts

SABER_celltyping.Rmd :
- Single cell phenotyping and expression quantificaiton (Fig.5,S5)
- Visualisation of cell populations and markers (Fig.5,S5)

