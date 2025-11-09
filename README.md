# VinaCarb_Cellulose
**Example of using (starting from the command line) Vina Carb for docking the crystalline surface of cellulose I alpha (it was created using cellulose-builder)**
**You need to install vinacarb from here: https://glycam.org/downloads/software / . Preliminary operations in **MGLTools** are also required (Grid Box coordinates, as well as pdbqt ligand and protein)**
**Usage**

1. Create a new conda environment 
2. Launch jupyter notebook
3. Run the presented code using your parameters
4.     Replace the examples of the ligand, protein, and vinacarb directories with yours (csv_path is the path where you want to save the csv with the energies based on the docking results)
5.     Replace the GridBox coordinates with your own
6.     Enter the number of models in each dock, as well as the number of runs.
7.     Pay attention to chi_coeff and chi_cutoff (enter your values)
8.     After launching the cell, make sure that it is correct (the line "Launching docking #..." will appear

**There is also an option for flexible amino acid residues, where a pathway to flexible pdbqt must be introduced.**

