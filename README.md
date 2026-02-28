## ⚠ Disclaimer

This project uses the **SMEFTsimtopU3l** model for FeynArts.  References -> {"arXiv:1709.06492", "arXiv:2012.11343"}, URLs -> {"https://github.com/SMEFTsim/SMEFTsim/releases/tag/v3.0.2", "https://github.com/SMEFTsim/SMEFTsim/tree/main"};

The model is **not included** in this repository.

Users must have:

- FeynArts installed.
- FeynCalc installed.
- The SMEFTsimtopU3l model properly installed locally.

Additionally, the path to the FeynArts model directory must be adapted in the code.  
In particular, the following line:

$FeynArtsModelPath = Append["C:\\Users\\USER\\AppData\\Roaming\\Wolfram\\Applications\\FeynCalc\\FeynArts\\Models"];


# SMEFT Diagram Generator

Interactive Mathematica interface for generating Feynman diagrams using FeynArts and FeynCalc. Just added amplitude calculations!

## What does this tool do?

This interface allows the user to:
- Select incoming and outgoing particles
- Choose tree-level or one-loop topologies
- Automatically generate Feynman diagrams
- Visualize them directly in Mathematica
- Export them to pdf.
- Automatically generate the amplitude.