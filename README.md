# Supplementary information
This repository contains the supplementary info, including sample locations, figures, data, and code for Kresse et al. XXXX. Code and raw data is included for species and genus level analyses.

## Abstract

As sea surface temperatures rise and ocean chemistry changes, it is important to understand how these shifts will impact marine life. Mollusks are integral parts of ocean ecosystems and compose a large portion of the shellfish industry; therefore changes to molluscan diversity will have widespread economic and ecological consequences. This study examines the effects of global warming and acidification on marine molluscan diversity across the mid-Piacenzian Warm Period (MPWP) in southeastern Virginia. The MPWP was an interval of warming that occurred from 3.264 to 3.025 Ma, during which sea surface temperatures rose approximately 3oC, and atmospheric CO2 concentrations were higher than pre-industrial levels. These conditions make it uniquely comparable to end-of-the century climate estimates and may provide insight into how modern mollusks will react to future climate change. Fossil molluscan assemblages from the Yorktown Formation that were deposited before, during, and after the MPWP were compiled from museum and field collections. Richness and diversity were quantified using rarefaction and Hill numbers, changes in species composition were measured using percent abundance, and community structure was assessed using Detrended Correspondence Analysis (DCA) and Permutational Analysis of Variance (PERMANOVA). Diversity peaks with warming and does not immediately return to pre-warming levels with subsequent cooling, and community structure differs significantly between each climate interval. Taxa exhibit species-specific responses in terms of abundance, with no uniform pattern across warming and cooling periods. As climate change intensifies, implications for modern molluscan fauna include long-term shifts in both diversity and community structure, which may have implications for ecosystem services.<br/>
<br/>
## Table of Contents

### Sample locations
* Latitude and longitude of sample locations in WGS 1984 (.csv)
  *  Also includes sample name, geologic member, locality, abbreviations, and locality ID according to Fig. 1

### Supplementary Figures
Supplementary figures with captions in .pdf format.

* Fig S1: Species level raw rarefaction
* Fig S2: Species level diversity accumulation curve (0D)
* Fig S3: Species level diversity accumulation curve (1D)
* Fig S4: Species level DCA

### Analyses and code
All supplementary information related to statistical analyses is organized by taxonomic level. Each taxonomic contains the following files:

* Raw species/genus abundance data
* **Hill Numbers (subfolder)**
   *  Code used to calculate species/genus level Hill numbers and diversity accumulation curves (.Rmd)
   * 	Observed Hill numbers for each geologic member (.csv)
   * 	Sample-size-based diversity accumulation curve data for each geologic member (.csv)

* **PERMANOVA (subfolder)**:
   *  4 sets of PERMANOVA were conducted: 1 comparing all members, and 3 pairwise comparisons between members. There is one subfolder for each comparison containing the following files
      * Code to conduct PERMANOVA (.Rmd)
      * PERMANOVA distance matrix (.csv)
   *  DCA coordinates for DC1 and DC2 (.csv)
   *  DCA coordinates for DC1 and DC2, transposed (.csv)


