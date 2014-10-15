# BIOMD0000000296: blub

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000296.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000296.git@20140916`


# Model Notes


This is the reduced model described in the article:  
**A synthetic Escherichia coli predator–prey ecosystem**   
Balagaddé FK, Song H, Ozaki J, Collins CH, Barnet M, Arnold FH, Quake SR, You
L._Mol Syst Biol._ 2008;4:187. Epub 2008 Apr 15. PMID:
[18414488](http://www.ncbi.nlm.nih.gov/pubmed/18414488);
DOI:[10.1038/msb.2008.24](http://dx.doi.org/10.1038/msb.2008.24)

Abstract:  
We have constructed a synthetic ecosystem consisting of two Escherichia coli
populations, which communicate bi-directionally through quorum sensing and
regulate each other's gene expression and survival via engineered gene
circuits. Our synthetic ecosystem resembles canonical predator–prey systems in
terms of logic and dynamics. The predator cells kill the prey by inducing
expression of a killer protein in the prey, while the prey rescue the
predators by eliciting expression of an antidote protein in the predator.
Extinction, coexistence and oscillatory dynamics of the predator and prey
populations are possible depending on the operating conditions as
experimentally validated by long-term culturing of the system in
microchemostats. A simple mathematical model is developed to capture these
system dynamics. Coherent interplay between experiments and mathematical
analysis enables exploration of the dynamics of interacting populations in a
predictable manner.

In the article the cell density is given in per 103 cells per microlitre. To
evade a conversion factor in the SBML implementation, the unit for the cell
densities was just left the same as for the AHLs A and A2 (nM).

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2012 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


