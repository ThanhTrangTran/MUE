# Medication Use Evaluation 

Background: This project is based on a real medication use evaluation performed in a 431–bed full-service hospital. 

Information: Mined synthetic EHR data from Synthea to determine rate of appropriate use of medication. Data was obtained through utilization of SQL in PostgreSQL. Visualization was created using Excel pivot tables and pivot charts. 

Insights:
The top 10 indications for the use of cefuroxime was determined to be mainly infectious, as is appropriate. Second-degree burns, while not specifically an infectious disease, is a condition that could lead to a bacterial infection and cefuroxime may have been used as a prophylaxis measure.
There were several indications in which the issue was not an infectious disease and thus cefuroxime was inappropriate. Further investigation as to why it was ordered in these specific situations is warranted.
For most of the inappropriate use of cefuroxime, the reason was due to a viral infection, not bacterial. Recommendation is to stop antibiotic once viral nature of the infection is discovered and proceed with symptom management instead.


Citation: Jason Walonoski, Mark Kramer, Joseph Nichols, Andre Quina, Chris Moesel, Dylan Hall, Carlton Duffett, Kudakwashe Dube, Thomas Gallagher, Scott McLachlan, Synthea: An approach, method, and software mechanism for generating synthetic patients and the synthetic electronic health care record, Journal of the American Medical Informatics Association, Volume 25, Issue 3, March 2018, Pages 230–238, https://doi.org/10.1093/jamia/ocx079
