Build an ML model for drug discovery using the ChEMBL database (https://www.ebi.ac.uk/chembl/) of bioactive molecules with drug-inducing properties.

**Query:** 'coronavirus' target protein *SARS coronavirus 3C-like proteinase*.\
**Preprocess:** drop na, categorise bioactivity by IC50 values (<1k active; >10k inactive; 1k-10k intermediate).\
**Exploration:** calculate Lipinski Rule descriptors, convert bioactivity to -log10(IC50), & visualise descriptors vs bioactivity (with MannWhitney-U significance testing):
- Molecular weight
- Octanol-water partition coefficient (LogP)
- Hydrogen bond donors
- Hydrogen bond acceptors


Based on tutorial and template Jupyter notebook by Chanin Nantasenamat, 
at the 'Data Professor' YouTube channel http://youtube.com/dataprofessor.
