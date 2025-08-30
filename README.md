# Type I Diabetes Research Project

## 📌 Overview
This project explores prohormone processing in Type I diabetes, conducted during my reserch internship with the Type-I pathology group at Helmholtz Institute in Munich under Dr.Teresea Rodriguez-Calvo.
The goal of this project was to investigate potential dysfunctions in insulin processing within the Type I diabetic pancreas and to present findings that may inform the development of improved treatment strategies and approaches for earlier detection of the disease.

---

## 🔬 Background
- Type-I Diabetes is an Autoimmune disease shown to result from both genetic and environmental factors where our immunesystem targets insulin producing Beta-Cells in the pancrease which leads to insulin deficiency, hyperglycemia, and Beta-cell dysfunctionality.
-  Type-I Diabetes requiress life long Insulin treatment. Type-I Diabetes affects approximately 9.5 million people globally, with children and adolescents being most affected. T1D incidence and prevalance have steadily increased, and the underlying causes are still not clear. 
- Prohormone processing research is critical in advancing our understanding of Type I diabetes because disruptions in insulin maturation represent some of the earliest molecular events in the disease. By identifying and characterizing these dysfunctions, researchers can uncover potential biomarkers for early detection, enabling interventions before complete pancreatic beta-cell loss.

For physicians, this knowledge supports more accurate diagnosis, patient stratification, and treatment monitoring, ultimately guiding personalized therapy. For the healthcare technology sector, these findings provide the foundation for developing innovative tools, from diagnostic assays and biosensors to AI-driven predictive models and digital monitoring platforms — that can translate biological insights into clinical practice.

In medicine more broadly, linking molecular dysfunction to patient outcomes has the potential to improve long-term management, reduce complications, and lower healthcare costs, making prohormone processing research highly relevant to the future of Type I diabetes care. 

---

## 🧪 Methods
- Study type: Lab research, data-analysis, and literature review. 
- Data: The Network for Pancreatic Organ Donors with Diabetes (nPOD) provides high-quality human pancreatic tissue for research.
- Their process includes:Harvesting pancreases from organ donors, Cutting small tissue blocks and embedding them in agarose. Sectioning thin slices using a vibratome, preserving: Islet architecture, Exocrine tissue, Microvasculature, Immune cell populations, Maintaining live slices in culture media for up to 12 hours. Stimulating a portion of slices with glucose to collect perfusate for downstream analysis.This system preserves the native tissue architecture and cellular interactions, providing a unique ex vivo platform for studying Type I diabetes in real human tissue.
- 15 Non-Diabetic Donors, 10T1D Donors and 5 Auto-Antibody Postive Donors. 

- Analysis:   QuPath + Python: Whole-slide images were imported into QuPath, a digital pathology platform.
Custom Python scripts were used to: Segment islets and surrounding tissue. Assess proinsulin-to-insulin ratios. Map immune cell infiltration. This workflow enables quantitative, reproducible analysis across multiple donors and markers

---

## 📊 Key Findings
- **Result 1: T1D islets showed impaired insulin and proinsulin secretion, in both unstimulated and stimulated conditions, indicating a loss of B-cell function.
- **Result 2: Aab+ donors maintained insulin expression, and had elevated proinsulin levels before stimulation, suggesting an accumulation due to a mal function in the conversion of proinsulin to insulin.

  <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/a652550d-4acc-4340-aa5c-a1aa10054804" />
  <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/a50caf3d-426c-486b-881d-d7dbf90f4b16" />

 -**Result 3: T1D and Aab+ islets maintained a substantial amount of PC2, showing that PC2 is still abundant in islets of people affected by T1D.

  <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/becd269e-1af1-414e-822d-fd399e1fc2e5" />

 - **Result 4: A decrease in proinsulin after stimulation in T1D and Aab+ donors correlates with previous studies of elevated proinsulin in blood. PC2 also decreases after stimulation which could mean it is secreted with proinsulin.

   <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/becd269e-1af1-414e-822d-fd399e1fc2e5" />
   <img width="400" height="500" alt="image" src="https://github.com/user-attachments/assets/becd269e-1af1-414e-822d-fd399e1fc2e5" />

 

---

## 🚀 Impact & Relevance
- **Clinical impact:**
- Potential Biomarker Development: Elevated proinsulin levels and altered PC2 dynamics may serve as early biomarkers of β-cell stress in Aab⁺ individuals before overt T1D diagnosis.
- Mechanistic Clues for Therapy: The observation that PC2 remains abundant in T1D islets suggests that not all processing machinery is lost, and that specific enzyme pathways could be therapeutically targeted or stabilized. The decrease in proinsulin and PC2 after stimulation raises the possibility that PC2 and proinsulin may be co-secreted, which needs further investigation.
- Relevance for Physicians & Translational Research: For clinicians, monitoring proinsulin: insulin ratios and enzyme activity may provide an early clinical tool for identifying patients at higher risk of rapid disease progression. For researchers and healthcare technology developers, these findings highlight new molecular targets (prohormone processing enzymes) for biomarker assays, biosensors, and therapeutic innovation.
- Value of the Pancreatic Slice Model: Demonstrating functional differences across donor types validates pancreatic slice models as powerful tools to study human T1D progression, bridging the gap between preclinical research and clinical application. Detecting this imbalance could provide a diagnostic window for earlier intervention.
- **Healthtech translation:** Our research on prohormone processing dysfunction in Type 1 Diabetes highlights elevated proinsulin levels and altered PC2 activity as potential early biomarkers of β-cell stress. These insights open opportunities for startups to develop diagnostic assays, biosensors, and predictive analytics tools that identify at-risk patients before clinical onset. By integrating proinsulin:insulin ratios into AI-driven monitoring platforms or clinical trial stratification, companies can deliver more precise and cost-effective care. This work provides a direct translational bridge between molecular biology and healthcare technology innovation.

---

## 👩‍🔬 My Role
- Designed: Protocol, Workflow, and Research presentation.  
- Conducted: Lab work, Data collection and Data Analysis 
- Presented findings at Helmholtz Research Institute  

---

## 📑 [View my full research presentation]
[Andreas Lab meeting.pptx](https://github.com/user-attachments/files/22059344/Andreas.Lab.meeting.pptx)

