# CHEMICAL-DATABASE-MANAGEMENT-SYSTEM-FROM-SMILES-CDMSS-

## Introduction:
### In the field of drug discovery, the ability to efficiently analyze and organize large sets of molecules is crucial. The use of a computational tool, such as the RDKit library, can streamline this process and provide valuable insights. This notebook demonstrates how to use RDKit and other essential libraries to convert SMILES strings into 3D SDF files, analyze molecular properties, and sort molecules into folders and subfolders. The notebook is designed to be a useful resource for researchers and scientists working in the field of drug discovery, providing a streamlined and efficient workflow for the analysis of large sets of molecules. Adios!!!!

![graphical_info](https://user-images.githubusercontent.com/45164491/213921484-d7221dff-fe04-40e4-be98-e4110a2c2b96.jpg)

*Note: a set of 500 Lipinski and ADME screened molecules are attached as an example. These molecules are Dock ready compounds!!!*

### Step-1:
> a) Read SMILES from the **".csv"** file and assign it to a dataframe **'df'**.  
> b) Calculate the molecular properties.

### Step-2:
This code block is adding the calculated properties stored in the empty lists (mw, clogp, clogs, tpsa, hba, hbd, and rot_bonds) to the dataframe as new columns, labeled 'MW', 'ClogP', 'ClogS', 'TPSA', 'HBA', 'HBD', and 'Rotatable Bonds'.

It then prints the entire dataframe so that you can see the calculated properties for each SMILES code in the dataframe.

*Note: This assumes that the dataframe 'df' and the empty lists are already defined and populated. Otherwise, errors will occur.*

### Step-3:
Save the list of molecular properties for the given SMILES in a CSV file named "Properties_for_smiles.csv" in the current working directory.

ENJOY STORING YOUR SCREENED COMPOUNDS USING THEIR SMILES!

---

## MIT License

MIT License

Copyright (c) 2024 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

### Personal Details

**Author**: [RIK GANGULY]  
**Email**: rikgangulybioinfo@gmail.com  
**Affiliation**: Computational Biology Laboratory, North-Eastern Hill University, Shillong
