# Kinetic model of the carbon and energy metabolis of E. coli growing under anaerobic conditions

## Repository content 

This repository contains two kinetic models, each in SBML and Copasi format:

- SBML file Model Version 1
- Copasi file Model Version 1
- SBML file Model Version 2
- Copasi file Model Version 2

These two models describe the central carbon and energy metabolism of E. coli growing under anaerobic conditions and were used in the following study to analyze the effect of enforced ATP turnover in the cell: 
"S. Boecker et al., An Integrated Approach to Decipher the Physiological Response of Escherichia coli Under High ATP Demand. 2021. Manuscript subbmitted for pubblication."

## Description
Both models contain 32 metabolites and 26 reactions and consist of two compartments (cytoplasm and external environment). The following major pathways are included: glucose phosphotransferase system (PTS), glycolysis, two anaplerotic reactions (PEP carboxylase and PEP carboxykinase), left and right branch of the tricarboxylic acid (TCA) cycle active under anaerobic conditions, the main fermentative pathways (leading to the fermentation products lactate, ethanol, acetate, formate and succinate), transport reactions between cytoplasm and external environment, a biomass synthesis reaction and finally a reaction (denoted by ATPM) for ATP hydrolysis whose activity depends on the level of the overexpression of the ATPase genes. 

As explained in the above work, model Version 1 and 2 differ for the introduction of regulatory terms in the PFL and PYK reaction and the adaptation of some parameters. 

More detailed information on the models can be found in the "Supplementary File 3" of the aforementioned paper. 


For Copasi documentation and download visit: 

http://copasi.org/

 

## License
Copyright [2021] [Giulia Slaviero, Steffen Klamt, Simon Boecker]

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.


