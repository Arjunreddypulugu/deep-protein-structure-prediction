# Protein Structure Modeling with Deep Learning (Tensorflow-Keras)

- Introduction and little-bit about proteins
Protein molecules are essential to all biological functions. All living things are consisted of cells. All proteins are consisted of chains of 21 fundamental units knows as amino acids. And those fundamental units (amino acids) of proteins are connected by a chemical bond known as peptide bonds (type of a covalent bond). DNA molecules in cells encode information about how proteins is formed by combining amino acids (fundamental building blocks of all protein molecules). So cells are the factories that produce different types of proteins, which are essential for life. Try this nice and short YouTube video to learn more about Proteins.

Some examples of protein molecules in human body include hemoglobin in blood, various types of enzymes that help with chemical reactions, antibodies in immune system, and collagens in bone structure, so on. Properties of different protein molecules are determined by its 3D structure. So, determining 3D structure is very important and classic problem in biology. Recent deep learning techniques are getting popular in protein structure detection problems.

In theory, there are 3 levels of protein structure representations.

Primary structure - represented by the sequence of amino acids.
Secondary structure - intermediate structure of proteins mainly consisted of major 2 types of secondary structure known as Alpha Helixes (sections of protein chain looks like spiral) and Beta Sheets (sections of protein chain looks like flat sheet).
Tertiary structure - 3D structure of the protein.
Quaternary structure - formed by combinations of several proteins.
Here I'm focusing on prediction of tertiary structure of a protein from the primary structure (sequences of amino acids). So here, I'm trying to build a neural network that can input sequence of amino acids and output 3D structure of proteins (coordinates of major atoms in proteins that define the overall shape of the protein).

Nice proteins datasets
Lot's protein 3D structures are organized in Protein Data Bank. And from these datasets, yearly competition is organized to find out best performing algorithm for protein structure prediction. This competition is known as CASP. Hence standardized datasets can be obtained through this competition to test machine learning algorithms. Furthermore, this CASP competition datasets were well organized and published in deep learning / machine learning friendly manner through a project call ProteinNet. So, here, I'm using a small sample of ProteinNet dataset.

Libraries used here
numpy
matplotlib
tensorflow v1.15 (keras)
Citation
Use this bibtex to cite this repository.

@misc{deep-protein-structure-modeling,
  title={Protein Structure Modeling with Deep Learning (Tensorflow-Keras)},
  author={N. Lakmal Deshapriya},
  year={2020},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/lakmalnd/deep-protein-structure-modeling}},
}
References (for sample data used in exercises)
Dataset for this pet project is obtained from ProteinNet. And GitHub repository of ProteinNet dataset can be accessed here, ProteinNet.

Dataset: Copyright (c) 2018 AlQuraishi Laboratory

AlQuraishi, M. ProteinNet: a standardized data set for machine learning of protein structure. BMC Bioinformatics 20, 311 (2019). https://doi.org/10.1186/s12859-019-2932-0
Other nice references
This paper is about Google Deepmind's neural network called "alphafold". These 2 videos also nicely explained "alphafold" in detail, (AlphaFold: Improved protein structure prediction and DeepMind AlphaFold)

Senior, A.W., Evans, R., Jumper, J. et al. Improved protein structure prediction using potentials from deep learning. Nature 577, 706–710 (2020). https://doi.org/10.1038/s41586-019-1923-7
This is another nice paper that I also got some inspiration for this pet project.

Wang S, Sun S, Li Z, Zhang R, Xu J. Accurate De Novo Prediction of Protein Contact Map by Ultra-Deep Learning Model. PLoS Comput Biol. 2017;13(1):e1005324. Published 2017 Jan 5. doi:10.1371/journal.pcbi.1005324
About
This repository is about prediction of tertiary structure of proteins from the primary structure of proteins (sequences of amino acids). So here, I'm trying to build a neural network that can input sequence of amino acids and output 3D structure of proteins (coordinates of major atoms in proteins that define the overall shape of the protein).

Topics
deep-learning protein-structure
Resources
 Readme
License
 MIT license
 Activity
Stars
 1 star
Watchers
 1 watching
Forks
 8 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
Jupyter Notebook
100.0%
Footer