# CobraPy - *Chlorella vulgaris* iFR947 Genome Scale Metabolic Model
##        Based On iCZ947 model of *Chlorella vulgaris*

# Arcticle: Generation of a metabolic-scale module of photosynthesis, photoinhibition and photoacclimation phenomena for *Chlorella vulgaris’* GSMs

A more detailed model of photosynthesis inside *Chlorella vulgaris*, using several quantum approaches as well as physiological knowledge to predict the metabolism in light-stress conditions.


### Authors: Rondón, Fabián Leonardo; Tibocha, Juan David; Godoy, Rubén Darío (2022)

#### Abstract:

Due to the photoinhibition phenomenon, microalgae culture efficiency strongly depends on light conditions. It modifies the concentration of the photosynthetic metabolites, besides decreasing the cell's growth rate. Therefore, it is mandatory to have a better understanding of physiological behaviour to pursue a better optimization of microalgae cultures. We proposed and evaluated a novel metabolic model using an exciton transport approach and physiological dynamics inside the iCZ947 model of ***Chlorella vulgaris***. Among several features to consider, the way the photons interact with the model is crucial not only because of the light uptake for metabolism but also how the solar energy is used and dissipated. This model allows for predicting several physiological phenomena, such as the increment in the xanthophyll cycle, pigments regulation as well as a de-novo synthesis of the D1 protein, depending on the incident light flux to the model


## Repository overview

├── README.md  
├── gitignore  
├── environment.yml for using in Anaconda  
├── Tutorial Cobrapy (Some tests on *Synechococcus elongatus* model)  
│   ├── CobraPy_Tutorial.ipynb  
│   ├── Model_iJB785.mat (Broddrick model)  
│   └── SolverCobra.txt  
├── Model iJB785 Analysis (*Synechococcus elongatus* model analyzed to extract the photosynthetic module and its proposal for photoinhibition)  
│   ├── Broddrick_Analysis_Model.ipynb  
│   └── CSV documents where the photosynthetic model is explained  
└── Model Chlorella Analysis (The previous iCZ947 model of *Chlorella v.*, and its modifications released in the iFR947 model)  
│   ├── BoundSenz (CSV documents analyzing the sensibility of several constraints in solver bounds)  
│   ├── Light emitted from a source (Raw data and interpolation of different light-sources spectra)  
│   │   └── Light Emission Index.txt → A recopilation of information about light-emmited spectra and its bibliography  
│   ├── PhotoActive Reactions (Raw data and interpolation of absorption spectrum for several light reactions in the metabolic model)  
│   │   └── Images Index.txt → A recopilation of information about light absorption spectra and its bibliography  
│   ├── Chlorella_Analysis_Model.ipynb → The development of the model and corresponding tests  
│   ├── Photoacive_ReactionData_Integration.ipynb → Algorithm to integrate light coefficients for absorption and emission spectrum, used as stoichiometric coefficients in the metabolic model  
│   └── CheckpointTest.json → first release of iFR947 Genome Scale Metabolic Model  


## About

Fabián Leonardo Rondón González is a Chemical Engineer graduated from the Universidad Nacional de Colombia, specialized on biochemical process modelling and bioinformatics. 
