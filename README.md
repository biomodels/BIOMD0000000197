# BIOMD0000000197: MDCKII_Transport

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000197.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000197.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000197 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


SBML model exported from PottersWheel on 2007-09-19 15:35:47.

The values for parameters and the inital concentrations of this model where
directly provided by the main author:  
Parameter values parameter | value | unit  
---|---|---  
p1 | 0.0025 | 1/min  
p2 | 0.0784 | 1/min  
p3 | 0.0013 | 1/min  
p4 | 0.0827 | 1/min  
p5 | 0.0091 | 1/min  
p6 | 0.000064 | 1/(nmole*min)  
p7 | 0.0397 | 1/min  
p8 | 1000 | nmole  
p9 | 0.0098 | 1/(nmole*min)  
p10 | 1.6 | 1/min  
p11 | 1000 | nmole  
p12 | 0.0003 | ml/min  
The basal chamber volume was taken as 1 ml, the apical as 1.5. As starting
values x1 was set to 88 nmole, all other species to 0.

  

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not.

  

To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


