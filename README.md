# MODEL1006230054: Lockwood2006_PKPD_AlzheimersDisease

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230054.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230054.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230054 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Application of clinical trial simulation to compare proof-of-concept study designs for drugs with a slow onset of effect; an example in Alzheimer's disease.**   
Lockwood P, Ewy W, Hermann D, Holford N. _Pharm Res_ 2006 Sep;23(9):2050-9
[16906456](http://www.ncbi.nlm.nih.gov/pubmed/16906456) ,  
**Abstract:**   
OBJECTIVE: Clinical trial simulation (CTS) was used to select a robust design
to test the hypothesis that a new treatment was effective for Alzheimer's
disease (AD). Typically, a parallel group, placebo controlled, 12-week trial
in 200-400 AD patients would be used to establish drug effect relative to
placebo (i.e., Ho: Drug Effect = 0). We evaluated if a crossover design would
allow smaller and shorter duration trials. MATERIALS AND METHODS: A family of
plausible drug and disease models describing the time course of the AD
assessment scale (ADAS-Cog) was developed based on Phase I data and literature
reports of other treatments for AD. The models included pharmacokinetic,
pharmacodynamic, disease progression, and placebo components. Eight
alternative trial designs were explored via simulation. One hundred replicates
of each combination of drug and disease model and trial design were simulated.
A 'positive trial' reflecting drug activity was declared considering both a
dose trend test (p < 0.05) and pair-wise comparisons to placebo (p < 0.025).
RESULTS: A 4 x 4 Latin Square design was predicted to have at least 80% power
to detect activity across a range of drug and disease models. The trial design
was subsequently implemented and the trial was completed. Based on the results
of the actual trial, a conclusive decision about further development was
taken. The crossover design provided enhanced power over a parallel group
design due to the lower residual variability. CONCLUSION: CTS aided the
decision to use a more efficient proof of concept trial design, leading to
savings of up to US 4 M dollars in direct costs and a firm decision 8-12
months earlier than a 12-week parallel group trial.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Lockwood P, Ewy W, Hermann D, Holford N. (2006) -
version=1.0**
](http://models.cellml.org/exposure/60366c003dba765e53609eaca35027fd)  
The original CellML model was created by:  
**James Lawson**   
j.lawson@auckland.ac.nz  
The University of Auckland  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


