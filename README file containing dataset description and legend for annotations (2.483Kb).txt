Ultrahigh Carbon Steel Microconstituent Annotations
===================================================

Brian DeCost, Matthew Hecht, Txai Sibley, Toby Francis, Bryan Webler, Yoosuf Picard, and Elizabeth Holm

This dataset consists of scanning electron micrographs accompanied by microconstituent annotations, and is intended as a community benchmark dataset for microstructure segmentation and clustering tasks.
The dataset consists of two groups of ultrahigh carbon steel (UHCS) micrographs: a set of images with broad field of view that contain complex microstructural features (proeutectoid grain boundary cementite network, spheroidite particles, Widmansttaten lath), and a higher-magnification set of images originally collected to quantify the cementite particle size distribution.

Both micrographs and annotations are stored as tif images. The directory structure is:

README.txt
uhcs/
  images/
  labels/
particles/
  images/
  labels/

UHCS semantic segmentation dataset
----------------------------------

The UHCS semantic microstructure segmentation dataset is an annotated subset of the larger UHCS dataset (Matthew D. Hecht, Brian L. DeCost, Toby Francis, Elizabeth A. Holm, Yoosuf N. Picard, and Bryan A. Webler. Ultrahigh carbon steel micrographs. https://hdl.handle.net/11256/940)

These micrographs were originally collected in support of the following study:

Matthew D. Hecht, Bryan A. Webler, and Yoosuf N. Picard. Digital image analysis to quantify carbide networks in ultrahigh carbon steels. Materials Characterization, 117:134â€“143. https://doi.org/10.1016/j.matchar.2016.04.012


The integer ids in the filenames for these micrographs and their annotations are the respective primary keys from the original UHCS dataset.

The legend for the tif annotations is:
-1: background (scale bar and imaging metadata)
0: ferritic matrix
1: proeutectoid carbide network
2: spheroidite particles
3: Widmanstatten lath


Particle segmentation dataset
-----------------------------

The particle segmentation dataset was originally collected in support of the following study:

Matthew D. Hecht, Yoosuf N. Picard, and Bryan A. Webler. Coarsening of inter and intragranular proeutectoid cementite in an initially pearlitic 2C-4Cr ultrahigh carbon steel. Metallurgical and Materials Transactions A, pages 1â€“16. 10.1007/s11661-017-4012-2

The magnification for these micrographs is such that 26 pixels corresponds to one micron.

The legend for the tif annotations is:
0: ferritic matrix
1: spheroidite (cementite) particle



