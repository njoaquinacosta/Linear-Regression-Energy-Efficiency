# Linear-Regression-Energy-Efficiency
"""
PROBLEM STATEMENT:

How should we design buildings (with respect to heating load) in the future?

Additional questions:

    1. Is there a relationship between building features and heating load?
    2. How strong is that relationship?
    3. Which are the strongest contributing features to heating load?
    4. Can heating load be predicted given a particular building design?

#######################################################################################################

SOURCE:

http://archive.ics.uci.edu/ml/datasets/Energy+efficiency

The dataset was created by Angeliki Xifara (angxifara '@' gmail.com, Civil/Structural Engineer) 
and was processed by Athanasios Tsanas (tsanasthanasis '@' gmail.com, Oxford Centre for Industrial 
and Applied Mathematics, University of Oxford, UK).

#######################################################################################################

FEATURES INFORMATION:

The dataset contains eight attributes (or features, denoted by X1...X8) and two responses 
(or outcomes, denoted by y1 and y2). The aim is to use the eight features to predict each 
of the two responses.

Specifically:

    X1 Relative Compactness
    X2 Surface Area
    X3 Wall Area
    X4 Roof Area
    X5 Overall Height
    X6 Orientation
    X7 Glazing Area
    X8 Glazing Area Distribution
    y1 Heating Load
    y2 Cooling Load

NOTE: 

    Feature names were changed to facilitate human readability.

#######################################################################################################

RELEVANT PAPERS:

    A. Tsanas, A. Xifara: 'Accurate quantitative estimation of energy performance 
    of residential buildings using statistical machine learning tools', Energy and
    Buildings, Vol. 49, pp. 560-567, 2012

#######################################################################################################

CITATIONS:

    1. Tsanas, A. Xifara: 'Accurate quantitative estimation of energy performance of 
    residential buildings using statistical machine learning tools', Energy and Buildings, 
    Vol. 49, pp. 560-567, 2012.

    For further details on the data analysis methodology:
    
    2. Tsanas, 'Accurate telemonitoring of Parkinson's disease symptom severity using nonlinear 
    speech signal processing and statistical machine learning', D.Phil. thesis, University of Oxford, 2012.
    
#######################################################################################################

ADDITIONAL SOURCES:

    1. Based upon this tutorial by Kevin Markham: https://github.com/justmarkham/DAT4/blob/master/notebooks/08_linear_regression.ipynb
"""
