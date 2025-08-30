Build an ML model for drug discovery using the ChEMBL database (https://www.ebi.ac.uk/chembl/) of bioactive molecules with drug-inducing properties.

<<<<<<< HEAD
**Query:** protein/organism of interest.\
=======
**Query** (in Coronavirus_tutorial): 'coronavirus' target protein *SARS coronavirus 3C-like proteinase*.\
>>>>>>> 777bf4b27142bb5c8ee61b6a4dabc811f6f557bf
**Preprocess:** drop na, select features (chembl_id, smiles, IC50), categorise bioactivity by IC50 values (<1k active; >10k inactive; 1k-10k intermediate).\
**Exploration:** calculate Lipinski Rule descriptors, convert IC50 to pIC50, visualise descriptors vs bioactivity (with MannWhitney-U significance testing):
- Molecular weight
- Octanol-water partition coefficient (LogP)
- Hydrogen bond donors
- Hydrogen bond acceptors
**ML:** prepare X and Y data, train model


Based on tutorial and template Jupyter notebook by Chanin Nantasenamat, 
at the 'Data Professor' YouTube channel http://youtube.com/dataprofessor.
