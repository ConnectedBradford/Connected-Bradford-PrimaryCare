# FDM_PrimaryCare
FDM repo

## Contains the scripts and data dictionary for the Primary Care . This is the GP datasets for Bradford and Airedale districts. 
##It contains approximately 1.2 million patients with the full clinical record. The dataset has been fully anonymised, but can link to other FDM's.
##There are a number of Primary Care FDM's. On order they are:

CB_FDM_PrimaryCare_v4 - build date 2022-03-05 - data up to 2022-02-27
CB_FDM_PrimaryCare_v5 - build date 2022-10-05 - data up to 2022-09-29
CB_FDM_PrimaryCare_V6 - build date 2023-01-01 - data up to 2022-12-30
CB_FDM_PrimaryCare_V7 - build date 2023-04-01 - data up to 2023-03-30
CB_FDM_PrimaryCare_V8 - build date 2023-10-17 - data up to 2023-10-11

The primary care FDM is made up of 17 source tables (summarised below and data dictionaries linked) from routinely collected primary care data from GP datasets for Bradford and Airedale Districts. for 1,176,111 individuals and their contacts, assessments and service types and dates. The dates relevant for this data are 1900/01/01 to 2023/10/11 
The source tables are largely populated by fields with the tbl_ where there is a person and a start and end date, and cb_ where there is no identifiable person, these are typically lookups.
In standard tables the data headings contained are: person, observation period and visit.  
In the source tables the data headings are: 
cb_srmedicationreadcodedetails
tbl_srappointment
tbl_srcode
tbl_srconfiguredlistoption
tbl_srimmunisation
tbl_srimmunisationcontent
tbl_srorganisation
tbl_srpatient
tbl_srpatientaddresshistory
tbl_srpatientregistration
tbl_srprimarycaremedication
tbl_srreferralin
tbl_srreferralout
tbl_srstaffmemberprofile
tbl_srvisit
tbl_visit_builder
For more information please go to the docs folder. This contains the Data dictionary .
There will be no identifiable information (such as names, date of birth, address,) available to the Connected Yorkshire project so patient confidentiality and privacy will be protected.  


