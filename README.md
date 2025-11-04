# Databricks-exemplum-VC
steps:
kaggle dataset >> load to AWS S3 backet >> ingest to Databriks >> prepare codes for bronze (load), silver (transform), gold (some aggregation) >>
prepare and run JOB with tasks >> table created

0. Kaggle dataset  StartUp Investments (Crunchbase) https://www.kaggle.com/datasets/arindam235/startup-investments-crunchbase
    <img width="1887" height="901" alt="image" src="https://github.com/user-attachments/assets/584e765e-5dab-41d5-a6a4-3a56564b0b34" />


1: Load raw CSV from S3 into a DataFrame
    <img width="1879" height="937" alt="image" src="https://github.com/user-attachments/assets/bdda44e9-345c-422b-9ce5-9ebc8b481afa" />

2.
    <img width="1778" height="717" alt="image" src="https://github.com/user-attachments/assets/b0009255-ceab-492c-9a82-8f37f364b193" />

4. find files for bronze, silver, gold into CODE in the current REPO
    <img width="1862" height="683" alt="image" src="https://github.com/user-attachments/assets/c1b1c996-b2ad-490e-8515-c99e0c254f58" />


5: JOB successfully finished
    <img width="1840" height="945" alt="image" src="https://github.com/user-attachments/assets/c1bbc22c-f7df-4454-a402-1f58a5b94522" />

