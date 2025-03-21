# Glaucoma-Outcomes-Survey
FHIR Structured Data Capture for Glaucoma Outcomes Survey (GOS)

This is a repo describing the [Fast Healthcare Interoperability Resources (FHIR) Structured Data Capture (SDC)](https://build.fhir.org/ig/HL7/sdc/) representation of the Glaucoma Outcomes Survey (GOS). This survey was validated in the study described in the publication, [Patient-Reported Outcomes for Minimally Invasive Glaucoma Surgery](https://pubmed.ncbi.nlm.nih.gov/38871267/), Singh K, Spaeth GL, Hays RD, Parke DW 2nd, Tarver ME, Eydelman M; Am J Ophthalmol. 2024 Oct;266:A1-A3. doi: 10.1016/j.ajo.2024.06.002. Epub 2024 Jun 12. PMID: 38871267.

The .json represntation of the pdf format developed by the study investigators was created using [NIH/NLM Lister Hill FHIR Tools](https://lhcforms.nlm.nih.gov/), specifically the [LHC Form Builder](https://formbuilder.nlm.nih.gov/). JSON stands for JavaScript Object Notation and is used for data interchange. To learn more about JSON check out [W3Schools Page](https://www.w3schools.com/whatis/whatis_json.asp).

## To View the SDC GOS Form
1. Download the file Glaucoma-Outcomes-Survey.LHC-Forms.json
2. Navigate to [LHC Form Builder](https://formbuilder.nlm.nih.gov/)
3. Select 'Start with Existing Form'
4. Select 'Import from Local Server' *Eventually we hope to be able to load from LOINC or from a FHIR Server
5. Navigate to the location for the GOS file downloaded in Step 1
6. Select the 'Preview' option from upper right corner of screen
7. In the preview, you can view the Rendered form view or the Json view
