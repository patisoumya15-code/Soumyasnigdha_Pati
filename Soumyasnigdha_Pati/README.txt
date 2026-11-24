SOIL FERTILITY CLASSIFICATION - BCA PBL

1. Project_Report.pdf: main chapter-wise report (edit personal details first).
2. Project_Presentation.pptx: classroom/viva presentation.
3. Dataset/: supplied CSV and its provenance README.
4. Source_Code/: full pipeline and 13 individual scripts.
5. Outputs/: generated charts, comparison results, matrices and example JSON.
6. Trained_Model/: saved fitted Random Forest model.
7. Taskwise_Assignments/: 13 Question / Code / Output PDFs.

INSTALL: pip install -r requirements.txt
RUN FULL ANALYSIS:
  python Source_Code/soil_fertility_project.py --data Dataset/soil_fertility_classification_1000.csv
NOTE: The full script writes into Source_Code/soil_fertility_results by default.
TO RUN A TASK FILE: python Source_Code/Task_01.py (replace 01 with 02 ... 13).
PREDICTION DEMO: python Source_Code/Task_13.py

SCIENTIFIC WARNING: teaching-only synthetic calibrated records and engineered labels.
Before submitting, confirm your department's required report template and sign-offs.
