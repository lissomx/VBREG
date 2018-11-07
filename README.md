# VBREG
Vector-Based REG v1.0

The VB-REG model is performing the fully statistical REG. The model aims to select attributes (the classic REG) as well as generating actual referental NPs (to discrib the target object within a domain)
The moedel regards REG as a special case of a generic approach to NLG.
For detail please the paper "Statistical NLG for Generating the Content and Form of Referring Expressions" (http://www.aclweb.org/anthology/W18-6561).

The model is origionally developed within C# (which is developed as a compoent of a big project). 

The evaluation outcomes in the paper "Statistical NLG for Generating the Content and Form of Referring Expressions" is based on the C# version.

For this repository, the VB-REG model is rewriten as an indipendent project (with python 3.6.5 and numpy 1.14.3), but only few tests were done on the python edition.

For any question or bugs reporting, please email me (xiao[dot]li [at] abdn[dot]ac[dot]uk).


# Manual:

REG_Samples.py is runable. It is the basic use case that how to load training corpus, train the VB-REG model, and generate the NPs.

To see the outcomes of the example, please simply run the file REG_Samples.py.
