# Data_Engineer_Akhil
PEI assignment

Steps followed for development :

Step 1) Refer document : **Test_with_code.pdf** -> Explored the data , read the requirements, wrote test cases to be covered. Have attached the code in this document for ease of evaluation.

Step 2) Refer document **Akhil_Bajpai_PEI.xlsx**  for architecture & planning. Started with loading data into databricks volume. Read those raw into raw_layer. Performed tests to ensure data integrity and correctness w.r.t source. Once all test cases passed moved with next step. 

Step 3) Refer **PEI_Code_Akhil.ipynb** For the entire code. Post loading data in layer 2 and performing tests. Transformation done, stored results in refined_layer and performed tests to ensure all looks good.

Step 4) Refer **PEI_Tests.ipynb**  for all test codes.

Step 5) Refer **Requirement-Document Mapping.pdf** to map all requirements & results. Created sales_mart, views and wrote SQL to compute the required data as mentioned in requirements.


Followed iterative TDD process:

1) Requirement -> Architecture (Akhil_Bajpai_PEI.xlsx) -> Tests (PEI_Tests.ipynb) -> Code (PEI_Code_Akhil.ipynb) -> Tests (PEI_Tests.ipynb) -> Code (PEI_Code_Akhil.ipynb) -> Final_Output

2) To address the respective test cases in PEI_Tests.ipynb code has been implemented in PEI_Code_Akhil.ipynb

3) Have maintained all the tests at one place PEI_Tests.ipynb and kept using the same throughout by updating it as required during the recurring test along with development and not segregated into files for each recurring step due to time constraint.
