# Deep Learning with Accelerated Computing (DLAC)

## Skill 5 – Dataset Audit and Visualisation

**Course Code:** 25CS3112E  
**Student Name:** G.S.S. Gyanadeep  
**Roll Number:** 2520080008  
**Branch:** AI & DS  
**University:** KL University

### Objective
To perform dataset auditing and visualisation on Indian traffic images by analysing image dimensions, image quality, class distribution and annotation availability.

### Tools and Technologies
- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Pillow (PIL)
- GitHub

### Practical Tasks Performed
1. Explored the Indian Traffic Dataset repository.
2. Inspected image dimensions and formats.
3. Checked for missing and unreadable images.
4. Visualised sample traffic images.
5. Inspected the existing traffic class distribution chart.
6. Analysed approximate class imbalance.
7. Generated image audit and class imbalance reports.
8. Exported audit results as CSV and TXT files.

### Audit Results

| Metric | Result |
|---|---:|
| Images inspected | 10 |
| Readable images | 10 |
| Missing images | 0 |
| Unreadable images | 0 |
| Sample images visualised | 5 |
| Traffic classes identified | 8 |
| Annotation files found | 0 |

### Class Distribution
The existing class distribution chart contains eight categories:
- Two wheeler
- Autorickshaw
- Car
- Bus
- LCV
- Truck
- Bicycle
- Pedestrian

The approximate class imbalance ratio observed from the chart is 12.67:1 (Car compared with Bus).

### Generated Reports
- `skill5_image_audit_summary.csv`
- `skill5_class_imbalance_report.csv`
- `SKILL5_FINAL_AUDIT_REPORT.txt`

### Limitation
The available repository did not contain the original annotation files. Therefore, bounding-box validation, annotation validation and exact annotation-based class-frequency calculations remain pending until the original annotated dataset is obtained.

### Conclusion
Image quality checks, sample visualisation, class distribution inspection and preliminary class imbalance analysis were performed successfully. Annotation-dependent validation requires the original annotated dataset.

### Repository
This folder contains the practical notebook and documentation for Skill 5.
