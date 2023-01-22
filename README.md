# CHEMICAL-DATABASE-MANAGEMENT-SYSTEM-FROM-SMILES-CDMSS-
## <span style="color:Black">Introduction: </span>
### <span style="color:purple"> In the field of drug discovery, the ability to efficiently analyze and organize large sets of molecules is crucial. The use of a computational tool, such as the RDKit library, can streamline this process and provide valuable insights. This notebook demonstrates how to use RDKit and other essential libraries to convert SMILES strings into 3D SDF files, analyze molecular properties, and sort molecules into folders and subfolders. The notebook is designed to be a useful resource for researchers and scientists working in the field of drug discovery, providing a streamlined and efficient workflow for the analysis of large sets of molecules. Adios!!!!</span>
![graphical_info](https://user-images.githubusercontent.com/45164491/213921484-d7221dff-fe04-40e4-be98-e4110a2c2b96.jpg)
<code style="background:cyan;color:black">*Note: a set of 500 Lipinski and ADME screened molecules are attached as example. These molecules are Dock ready compounds!!! </code>
### *Step-1:* 
> #### a) Read smilesfrom the csv file and assign it to a dataframe 'df'.
> #### b) Calculate the molecular properties. 
### Step-2: 
#### This code block is adding the calculated properties that were stored in the empty lists (mw, clogp, clogs, tpsa, hba, hbd, and rot_bonds) to the dataframe as new columns, labeled 'MW', 'ClogP', 'ClogS', 'TPSA', 'HBA', 'HBD', and 'Rotatable Bonds'.
#### It then prints the entire dataframe so that you can see the calculated properties for each SMILES code in the dataframe.
#### Please note that this code block assumes that the dataframe 'df' and the empty lists (mw, clogp, clogs, tpsa, hba, hbd, and rot_bonds) are already defined and populated. If they are not defined, you will get an error while running this block of code.
### Step-3:
#### Save the list of molecular properties for the given smiles in a csv file named "Properties_for_smiles.csv", in the current working directory.
> ENJOY STORING YOUR SCREENED COMPOUNDS USING THEIR SMILES
