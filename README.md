# Databricks-exemplum-VC
steps:
kaggle dataset >> load to AWS S3 backet >> ingest to Databriks >> prepare codes for bronze (load), silver (transform), gold (some aggregation) >>
prepare and run JOB with tasks >> tables created

0. Kaggle dataset  StartUp Investments (Crunchbase) https://www.kaggle.com/datasets/arindam235/startup-investments-crunchbase
    <img width="1887" height="901" alt="image" src="https://github.com/user-attachments/assets/584e765e-5dab-41d5-a6a4-3a56564b0b34" />


1: Load raw CSV from S3 into a DataFrame
    <img width="1879" height="937" alt="image" src="https://github.com/user-attachments/assets/bdda44e9-345c-422b-9ce5-9ebc8b481afa" />

2. Create Databriks table from S3
   <img width="1909" height="699" alt="image" src="https://github.com/user-attachments/assets/7ed0175a-3922-42ca-baa7-345c35f528d7" />

3. Find files for bronze, silver, gold into CODE in the current REPO
Pipeline_vc_2/ETL_VC(transformations)/bronze/bronze_load_vc.ipynb
Pipeline_vc_2/ETL_VC(transformations)/silver/silver_transfom_vc.ipynb
Pipeline_vc_2/ETL_VC(transformations)/gold/gold_agg_vc.ipynb
    <img width="1862" height="683" alt="image" src="https://github.com/user-attachments/assets/c1b1c996-b2ad-490e-8515-c99e0c254f58" />
    <img width="1895" height="863" alt="image" src="https://github.com/user-attachments/assets/3b2697b5-3e0a-49be-b277-8fa44fea63e5" />

4. JOB successfully finished
    <img width="1840" height="945" alt="image" src="https://github.com/user-attachments/assets/c1bbc22c-f7df-4454-a402-1f58a5b94522" />

5. tables created
