# MODEL1409050001: MODEL1409050001

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1409050001.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1409050001.git@20140916`

## Usage

Importing the model package.

`import MODEL1409050001 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes

    
    
    The model corresponds to the Table 4 and the last column of table 5 of publication (PMID: 24085837, DOI: 10.1099/mic.0.071340-0).
    
    
    Mathematical	Definition			
    symbol/abbreviation				
    				
    				
    Mathematical symbols				
    				
    Keq		Equilibrium constant			
    Ki		Inhibition constant			
    Km		Affinity constant			
    v		Predicted enzyme activities			
    Vf		Maximal enzyme activities under saturating substrate and activator			
    		conditions, and in the absence of inhibitors			
    h		Hill coefficient
    k		Rate constant			
    				
    Abbreviations				
    				
    ACET		Acetaldehyde			
    ADH		Alcohol dehydrogenase			
    AK		Adenylate kinase			
    ATPcons		ATP consuming reactions			
    bPG		1,3-bisphosphoglycerate			
    ENO		Enolase		 	
    ETOHcy		Cytoplasmic ethanol 			
    ETOHex		Extracellular ethanol			
    ETOHexp		Ethanol transport			
    GAP		Glyceraldehyde 3-phosphate 			
    GAPD		Glyceraldehyde 3-phosphate dehydrogenase 			
    GF		Glucose facilitator			
    GK		Glucokinase 			
    GLUCcy		Cytoplasmic glucose			
    GLUCex		Extracellular glucose			
    GLUC6P		Glucose 6-phosphate			
    GPD		Glucose 6-phosphate dehydrogenase			
    KDPG		2-keto-3-deoxy-6-phosphogluconate			
    KDPGA		2-keto-3-deoxy-6-phosphogluconate aldolase			
    PDC		Pyruvate decarboxylase			
    PEP		Phosphoenolpyruvate			
    PGD		6-phosphogluconate dehydratase 			
    PGK		3-phosphoglycerate kinase			
    PGL		6-phosphogluconolactonase			
    PGLACTON		6-phosphogluconolactone			
    PGLUCONATE	6-phosphogluconate			
    PGM		Phosphoglycerate mutase			
    P3G		3-phosphoglycerate			
    P2G		2-phosphoglycerate			
    PYK		Pyruvate kinase			
    PYR		Pyruvate


