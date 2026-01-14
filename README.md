# molecular-featurization-lab
Comparative chemical featurization using RDKit for molecular property prediction and catalyst screening
# Molecular Representation & Featurization Lab

This project explores different methods of converting chemical structures 
(SMILES) into machine-readable vectors, a core requirement for the 
**LowDataML** network.

### Features:
- **Circular Fingerprints (ECFP4):** Capturing local atom environments.
- **Substructure Keys (MACCS):** Identifying specific functional groups.
- **Physical Descriptors:** Calculating LogP and Molecular Weight using RDKit.

### The Münster Context (Sterics & Catalysis):
The script includes a pre-processing step to **Add Hydrogens**, which is 
essential for calculating 3D-sensitive descriptors. This reflects an 
understanding of the **Glorius Group's** focus on high-fidelity molecular 
representation for organic catalysis.

### Keywords:
`RDKit`, `SMILES`, `Cheminformatics`, `Molecular Descriptors`, `Catalysis`
