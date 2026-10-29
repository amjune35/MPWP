# Supplementary Information
This repository contains the supplementary info, including sample locations, figures, data, and code for Kresse et al. XXXX. Code and raw data is included for species and genus level analyses.

## Abstract

As sea surface temperatures rise and ocean chemistry changes, it is important to understand how these shifts will impact marine organisms. Mollusks play an important role in ocean ecosystems and represent a substantial portion of the shellfish industry; therefore, changes to molluscan diversity will have widespread economic and ecological consequences. In this study, we examine shifts in marine bivalve and gastropod diversity across the mid-Piacenzian Warm Period (MPWP) in southeastern Virginia. The MPWP was an interval of warming that occurred from 3.264 to 3.025 Ma, during which sea surface temperatures rose approximately 3oC, and atmospheric CO2 concentrations were higher than pre-industrial levels. These conditions make it uniquely comparable to end-of-the century climate estimates and may provide insight into how modern mollusks will respond to future climate change. We compiled data on fossil bivalve and gastropod assemblages from time intervals before, during, and after the MPWP from museum and field collections. Richness and diversity were quantified using Hill numbers and community structure was assessed using Detrended Correspondence Analysis (DCA) and Permutational Analysis of Variance (PERMANOVA). Average Hill numbers of the order q = 1 suggest diversity doubles during the MPWP and does not immediately return to previous levels. Similarly, community structure differs significantly between each time interval; species composition and abundance do not return to previous conditions after the MPWP.  As climate change intensifies, implications for modern molluscan fauna include long-term shifts in both diversity and community structure, which may have implications for ecosystem services.<br/>
<br/>
## Table of Contents

### Supplementary Tables and Figures
Supplementary tables and figures with captions in .pdf format. Sample location data is formatted as .csv.<br/>
<br/>
* Table S1: Latitude and longitude of sample locations in WGS 1984
  *  Also includes sample name, geologic member, locality, abbreviations, and locality ID according to Fig. 1
* Table S2: ANOVA summary tables for species- and genus-level 1D values, with caption

* Fig S1: Species level raw rarefaction
* Fig S2: Species level diversity accumulation curve (0D)
* Fig S3: Species level diversity accumulation curve (1D)
* Fig S4: Species level DCA<br/>
<br/>

### Analyses and Code
All supplementary information related to statistical analyses is organized by taxonomic level, with the exception of the analysis of extant species see (OBIS Environmental Analysis). Each taxonomic contains the following files:<br/>
<br/>
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
 <br/>

 ### OBIS Environmental Analysis
 All supplementary information related to statistical analyses of extant species using OBIS is located in the FOLDER NAME. The folder contains the following files:
 <br/>
 * Table of species present in samples (.csv)
 * Code to prepare, extract, and process environmental data from OBIS (.Rmd)
 * Resulting environmental summary statistics for all extant taxa (.csv)


