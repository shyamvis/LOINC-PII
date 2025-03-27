# Abstract

Provisioning clinical data for research frequently necessitates the suppression of identifying information, including personally identifiable information (PII) especially when providing safe harbor and limited data. Identifying information in coded (structured) data in electronic health records (EHRs) is uncommon, except in data coded with Logical Observation Identifiers, Names, and Codes (LOINC). We developed a two-step process consisting of rule-based queries and manual physician review to identify LOINC codes with potential identifying information. We identified 1,000 LOINC codes that were categorized into PII and identifying information about healthcare providers and facilities. This list of codes is publicly available and will be a valuable resource for enhancing deidentification workflows to comply with the Health Insurance Portability and Accountability Act (HIPAA) regulations. 


-------------------------------------
The table in this repo has seven columns: LOINC_NUM, LONG_COMMON_NAME, PROPERTY, CLASS, Keyword, Category, and CLASSTYPE. 
