Build an ML model for drug discovery using the ChEMBL database (https://www.ebi.ac.uk/chembl/) of bioactive molecules with drug-inducing properties.

**Query:** \
'acetylcholinesterase' *Human Acetylcholinesterase*\
**Preprocess:** 
*script:* CDD_ML_Part_1_Bioactivity_Preprocessing \
*outputs:* (raw) bioactivity_data.csv; (cleaned) bioactivity_preprocessed_data.csv\
**Exploration:** \
*input:* bioactivity_preprocessed_data.csv\
*script:* CDD_ML_Part_2_Exploratory_Data_Analysis\
**ML:** 
*script:* CDD_ML_Part_3_Acetylcholinesterase_Descriptor_Dataset_Preparation


Based on tutorial and template Jupyter notebook by Chanin Nantasenamat, 
at the 'Data Professor' YouTube channel http://youtube.com/dataprofessor.