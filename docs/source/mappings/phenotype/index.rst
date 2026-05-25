Phenotype Mappings
==================

Phenotype Mapping to HPO Terms 
------------------------------
  
The phenotype fields present across the four TREAT-NMD core datasets - the SMA Core Dataset, the DMD Core Dataset, the LGMD Core Dataset, and the general Neuromuscular Disease (sNMD) Dataset - were systematically extracted and mapped to terms from the Human Phenotype Ontology (HPO). 

Extraction 
----------
  
All phenotype-related fields (i.e. the set of observable characteristics or traits of an individual) were identified and extracted from each of the four datasets. This covered clinical observations, comorbidities, and any other data elements capturing signs, symptoms, or clinically observable traits across the SMA, DMD, LGMD, and sNMD datasets. 

Mapping methodology 
-------------------
  
Extracted phenotype terms were mapped to HPO terms using the EMBL-EBI Ontology Lookup Service (OLS). For each phenotype, OLS was queried to identify the most appropriate matching HPO term based on label and synonym matching. Where an exact label match was available, it was preferred. Where multiple candidate terms were returned, the most specific applicable term was selected. Further, for some terms we have identified cross references to other ontologies (e.g. SNOMED) 

Cross-validation 
----------------

To ensure mapping quality and consistency, all mappings were cross-checked against independent mappings produced by colleagues with prior experience in HPO annotation. Discrepancies between mappings were reviewed and resolved through discussion, with the agreed term recorded as the final mapping. 

Output 
------

The result is a curated set of HPO mappings covering the phenotype content of all four TREAT-NMD core datasets, providing a standardised, interoperable representation of the clinical phenotype data captured within the TREAT-NMD registry ecosystem. 

Impact and Related Work 
-----------------------
 
This mapping has also prompted a systematic cross-checking and review of EURO-NMD Registry data elements, with a particular focus on clinical assessments. For example, beyond the collection of Human Phenotype Ontology (HPO) phenotype codes, ongoing work includes mapping items from the existing baseline questionnaire on mobility and general physical functioning to corresponding HPO terms. 

