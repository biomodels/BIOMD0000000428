# BIOMD0000000428: MODEL1209130000

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000428.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000428.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000428 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Achcar2012 - Glycolysis in bloodstream form T. brucei

Kinetic models of metabolism require quantitative knowledge of detailed
kinetic parameters. However, the knowledge about these parameters is often
uncertain. An analysis of the effect of parameter uncertainties on a
particularly well defined example of a quantitative metablic model, the model
of glycolysis in bloodstream form Trypanosoma _brucei_ , has been presented
here.

This model is described in the article:

[Dynamic modelling under uncertainty: the case of Trypanosoma brucei energy
metabolism.](http://identifiers.org/pubmed/22379410)

Achcar F, Kerkhoven EJ; SilicoTryp Consortium, Bakker BM, Barrett MP,
Breitling R.

PLoS Comput Biol. 2012 Jan; 8(1):e1002352.

Abstract:

Kinetic models of metabolism require detailed knowledge of kinetic parameters.
However, due to measurement errors or lack of data this knowledge is often
uncertain. The model of glycolysis in the parasitic protozoan Trypanosoma
brucei is a particularly well analysed example of a quantitative metabolic
model, but so far it has been studied with a fixed set of parameters only.
Here we evaluate the effect of parameter uncertainty. In order to define
probability distributions for each parameter, information about the
experimental sources and confidence intervals for all parameters were
collected. We created a wiki-based website dedicated to the detailed
documentation of this information: the SilicoTryp wiki
(http://silicotryp.ibls.gla.ac.uk/wiki/Glycolysis). Using information
collected in the wiki, we then assigned probability distributions to all
parameters of the model. This allowed us to sample sets of alternative models,
accurately representing our degree of uncertainty. Some properties of the
model, such as the repartition of the glycolytic flux between the glycerol and
pyruvate producing branches, are robust to these uncertainties. However, our
analysis also allowed us to identify fragilities of the model leading to the
accumulation of 3-phosphoglycerate and/or pyruvate. The analysis of the
control coefficients revealed the importance of taking into account the
uncertainties about the parameters, as the ranking of the reactions can be
greatly affected. This work will now form the basis for a comprehensive
Bayesian analysis and extension of the model considering alternative
topologies.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1209130000](http://identifiers.org/biomodels.db/MODEL1209130000) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


