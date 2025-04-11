# Patient Reported Outcomes Surveys for Vision

This GitHub repository highlights highlights the [Fast Healthcare Interoperability Resources (FHIR) Structured Data Capture (SDC)](https://build.fhir.org/ig/HL7/sdc/) representation for two validated, structured data capture surveys in vision health. The topics are Glaucoma surgery outcomes and Lasik eye surgery outcomes. 

The .json representation of the pdf formats of each survey instrument was developed by the study investigators using [NIH/NLM Lister Hill FHIR Tools](https://lhcforms.nlm.nih.gov/), specifically the [LHC Form Builder](https://formbuilder.nlm.nih.gov/). JSON stands for JavaScript Object Notation and is used for data interchange. To learn more about JSON check out [W3Schools Page](https://www.w3schools.com/whatis/whatis_json.asp).

## Glaucoma-Outcomes-Survey (GOS)
FHIR Structured Data Capture for Glaucoma Outcomes Survey (GOS)

This survey was validated in the study described in the publication, [Patient-Reported Outcomes for Minimally Invasive Glaucoma Surgery](https://pubmed.ncbi.nlm.nih.gov/38871267/), Singh K, Spaeth GL, Hays RD, Parke DW 2nd, Tarver ME, Eydelman M; Am J Ophthalmol. 2024 Oct;266:A1-A3. doi: 10.1016/j.ajo.2024.06.002. Epub 2024 Jun 12. PMID: 38871267.

### To View the SDC GOS Form
1. Download the file Glaucoma-Outcomes-Survey.LHC-Forms.json [here](https://github.com/goetzke2/Glaucoma-Outcomes-Survey/blob/main/Glaucoma-Outcomes-Survey.LHC-Forms.json)
2. Navigate to [LHC Form Builder](https://formbuilder.nlm.nih.gov/)
3. Select 'Start with Existing Form'
4. Select 'Import from Local Server' *Eventually we hope to be able to load from LOINC or from a FHIR Server
5. Navigate to the location for the GOS file downloaded in Step 1
6. Select the 'Preview' option from upper right corner of screen
7. In the preview, you can view the Rendered form view or the Json view

## Patient Reported Outcomes with LASIK (PROWL)
FHIR Structured Data Capture for Laser In Situ Keratomileusis Studies

This survey was validated in the study described in the publication, [Symptoms and Satisfaction of Patients in the Patient-Reported Outcomes With Laser In Situ Keratomileusis (PROWL) Studies](https://pubmed.ncbi.nlm.nih.gov/27893066/). This study includes a pre-operative survey and a post-operative survey. 

### To View the SDC PROWL Form
1. Download the files
     - [Pre-op](https://github.com/goetzke2/Vision-Patient-Reported-Outcomes-Surveys/blob/main/Patient-reported-outcomes-with-LASIK---pre-operative-panel-%5BPatient-reported-outcomes-with-LASIK%5D.LHC-Forms.json)
     - [Post-op](https://github.com/goetzke2/Vision-Patient-Reported-Outcomes-Surveys/blob/main/Patient-reported-outcomes-with-LASIK---post-operative-panel-%5BPatient-reported-outcomes-with-LASIK%5D.LHC-Forms.json)
3. Navigate to [LHC Form Builder](https://formbuilder.nlm.nih.gov/)
4. Select 'Start with Existing Form'
5. Select 'Import from Local Server' *Note that this survey is also available as FHIR R5, R4, and STU3 format
6. Navigate to the location for the survey file(s) downloaded in Step 1
7. Select the 'Preview' option from upper right corner of screen
8. In the preview, you can view the Rendered form view or the Json view
