# CellProfiler Pipeline 2D segmentation
This is an automated pipeline for the subcellular segmentation of 7 different organelles, in 2D dimensions:
Nuclei (NU)
Lysosomes (LS)
Mitochondria (MT)
Golgi (GL)
Peroxisomes (PO)
Endoplasmic Reticulum (ER)
Lipid Droplets (LDs)

The pipeline is divided in three parts:
PART-1 [CellP-2D_v1wNU_PART-1of3_03202022]:Is deputed for the identification of Nuclei, whole soma and cytoplasm.
PART-2 [CellP-2D_v1wNU_PART-2of3_03202022]: Is assigned to identify 6 organelles (LS, MT, GL, PO, ER, and LD).
PART-3 [CellP-2D_v1wNU_PART-3of3_03202022]: Is uses the objects previusly identified to measure contacts in between organelles (1 to 1), the distribution of the organelles and the contacts, and it contains the export module to csv file. 

Please reffer to the notes at each module.
