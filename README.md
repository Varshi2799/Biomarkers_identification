# Biomarkers_identification

What is a biomarker?

Biomarkers are indicators of disease occurrence and progression. They can be used to assess normal biological and pathogenic processes or pharmacologic responses to a therapeutic intervention and, in some cases, may serve as potential drug and prognostic targets.

Biomarkers help not only in disease diagnosis (diagnostic biomarkers) but also in identifying potential treatments and tracking disease progression, regression, and outcome after an intervention.

In modern healthcare, biomarkers are an integral part of approaches to monitoring patient health and condition, providing researchers with a means of predicting treatment response.

## CLASSIFICATION OF BIOMARKERS:
Biomarkers have been classified based on different parameters, including their characteristics, clinical applications, and finally, genetic and molecular biology methods

**Genetic and molecular biology biomarkers**: Measurable indicators that provide insights into an individual's genetic makeup, biological processes, or disease states. These biomarkers play a crucial role in medical diagnostics, disease monitoring, and personalized treatment strategies.

Type 0, Type1 and Type 2 Biomarkers
According to Genetics and Molecular Biology methods, biomarkers can be classified as follows 

## Type 0 Biomarkers
Also known as natural history biomarkers. These biomarkers help measure the natural history of a disease and correlate over time with known clinical indicators.
An example of a type 0 biomarker is the measurement of serum creatinine to measure kidney function or monitor injury to kidneys.

## Type 1 Biomarkers
These are drug activity biomarkers, and they indicate the effect of drug intervention. They may be further divided into:
**Efficacy biomarkers** – indicating the therapeutic effects of a drug;
**Mechanism biomarkers** – giving information about the mechanism of action of a drug;
**Toxicity biomarkers** – indicating the toxicological effects of a drug.
Examples of type 1 biomarkers include blood glucose levels (efficacy biomarker) to monitor the effects of insulin treatment [4] and cytokines (mechanism biomarker) in autoimmune diseases such as rheumatoid arthritis.

## Type 2 Biomarkers
These are surrogate markers (also known as surrogate endpoints) that serve as a substitute for a clinical outcome of a disease and also help predict the effect of a therapeutic intervention. Such markers may correlate with clinical endpoints but may not have a guaranteed relationship.

Cholesterol in heart disease is one example of a Type 2 biomarker—where elevated levels are correlated with increased risk of heart disease, but the relationship is not always present, as there are cases of heart disease with low cholesterol levels, and some patients do not develop heart disease despite high levels of cholesterol.


## Prognostic, Predictive, Pharmacodynamic and Surrogate End-point Biomarkers
Another classification of biomarkers divides them into 4 classes: 
Prognostic. 
Predictive.
Pharmacodynamic.
Surrogate end-point.


**Prognostic Biomarkers**

Prognostic (Greek) means “fore-knowing or foreseeing.” Prognostic biomarkers are the ones that suggest the likely outcome of a disease in an untreated individual.

An example of a prognostic biomarker is the mutation status of PIK3CA in HER-2 positive metastatic breast cancer, where individuals with mutated PIK3CA have been found to have lower rates of disease-free survival.

**Predictive Biomarkers**

Predictive biomarkers are used to identify those patients who are likely to have a positive clinical outcome in response to a given treatment. Thus, with the help of predictive biomarkers, it is possible to give a particular therapy to the patients for which it is most likely to be effective. 

Erlotinib maintenance treatment is a therapeutic intervention used to treat advanced non–small-cell lung cancer. For patients with an EGFR mutation in the tumor, progression-free survival is significantly lower following erlotinib treatment than for those without an EGFR mutation receiving the same treatment. This makes EGFR mutation status a predictive biomarker for response to erlotinib treatment.

**Pharmacodynamic Biomarkers**

These biomarkers help in determining the pharmacological effects of a drug and can inform if the treatment is working as expected. 

PI3K inhibitors are used to treat a variety of cancers. The PI3K signaling pathway includes multiple downstream targets, including AKT. On activation of the PI3K pathway, AKT becomes phosphorylated, and therefore phosphorylated AKT (pAKT) can act as a pharmacodynamic biomarker to confirm that Pi3K inhibitor treatment is indeed inhibiting the PI3K pathway. If pAKT levels drop, the inhibitor is working. 

**Surrogate Biomarkers**

Surrogate biomarkers are identical in all but name to type 2 biomarkers, so see the section above for more detail. Another example of a surrogate biomarker is blood pressure for cardiac disease. 

To be useful, surrogate markers should be an effective substitute for the clinical outcome, and effects on the substitute should predict clinical outcomes.

However, there is a possibility, because the biomarker is just a surrogate, that the effect of pharmacological therapeutics on the surrogate may not affect the outcome, limiting its usefulness.

**SPECIFIC CASE STUDY: Identification of BCR-ABL as a driver of CML**

The identification of the Philadelphia chromosome in cells from individuals with chronic myelogenous leukemia (CML) led to the recognition that the BCR-ABL tyrosine kinase causes CML.

This in turn led to the development of imatinib mesylate, a clinically successful inhibitor of the BCR-ABL kinase.

This was the first human cancer in which a consistent genetic abnormality was demonstrated to cause the disease.

BCR-ABL is a fusion gene formed when parts of two different chromosomes — chromosome 9 and chromosome 22 — break off and swap places. This specific abnormal chromosome is called the Philadelphia chromosome (Ph).

BCR (Breakpoint Cluster Region): From chromosome 22

ABL (Abelson murine leukemia viral oncogene homolog 1): From chromosome 9

This gene fusion produces a BCR-ABL protein, an abnormal tyrosine kinase that is always active, leading to uncontrolled cell division.

1960: The Philadelphia chromosome was discovered by Nowell and Hungerford in patients with chronic myeloid leukemia (CML). This was the first consistent chromosomal abnormality associated with cancer.

Significance: First genetic link to cancer ever found — a breakthrough in understanding cancer as a genetic disease.

1980s–1990s: Molecular studies revealed that the translocation created the BCR-ABL fusion gene. 

Key Insight: The fusion protein acts like a switch that is stuck "on," driving cancer growth by promoting rapid and uncontrolled white blood cell proliferation. 


**Plan of the project:**

-> **Identification of relevant genes:** In relation to a particular network or affecting a phenomenon/phenotype

-> **Interactions/connections between them:** To understand how these genes interact with one another and have an impact on the end points

-> **Direction of interaction:** Considering the example of 2 genes, gene A and gene B, we are to determine:

-If gene A-> gene B (Could be a positive/negative interaction)

-If gene B -> gene A (Could be a positive/negative interaction)

-If a feedback loop is observed

-> **Strength of the interacton:** The impact that a gene has on its downstream is to be determined

-> **Network Coverage:** Based on these imputs, the network is to be built

-> **Validation** Literature validation of the network created.


## Datasets come across that can help with the scope of the project:

--

DABS datasets: The Diagnostic and Biomarkers Statistical (DABS) Center is a specialized research unit focused on the statistical evaluation, validation, and advancement of diagnostic tools and biological markers (biomarkers) used in clinical medicine and translational research.

Function in relation to biomarkers:
Biomarker Validation:
Helps determine whether a biomarker can reliably detect or predict a disease, progression, or response to treatment.
Focuses on both analytical validity (how accurately and reliably the test measures the biomarker) and clinical validity (how well the biomarker predicts a clinical outcome).

Several publicly available datasets designed for practicing statistical methods in medical diagnostics and biomarker research. These datasets are particularly useful for researchers and students aiming to understand and apply statistical techniques in the context of medical data.


Apply Statistical Methods for Biomarker Validation
Test or learn how to use advanced statistical methods:
Logistic regression to model disease status as a function of biomarkers.
Time-dependent ROC curves for biomarkers in survival analysis.
Net Reclassification Improvement (NRI) to assess whether a new biomarker improves patient classification.
Decision Curve Analysis (DCA) to weigh clinical usefulness.

**Relevant to our project**
Use the datasets to compare the performance of two or more biomarkers or test algorithms:
Is biomarker A better than biomarker B?
Does combining A + B improve diagnosis?
Does adding clinical features (age, symptoms) improve performance?

https://research.fredhutch.org/diagnostic-biomarkers-center/en/datasets.html 

## Project plan and status:

**Finalising a pathway:**
Pathway selected: HR Pathway
Reasoning: Knowledge about DNA damage agents and the different DNA repair mechanisms.
Biomarkers from HR pathway genes can signal DNA repair proficiency, tumor aggressiveness, or therapeutic vulnerabilities.
Understanding gene contributing to genomic stability.

**Finalising the list of genes**

## Homologous Recombination (HR) Pathway Gene List

| **Gene**   | **Functionality in HR Pathway** |
|------------|----------------------------------|
| **ATM**    | A kinase rapidly activated by DNA double-strand breaks, initiating the HR repair response via phosphorylation of key repair proteins. |
| **ATR**    | A sensor kinase activated by replication stress and single-stranded DNA that stabilizes stalled replication forks and promotes HR repair. |
| **ATRX**   | A chromatin remodeler implicated in HR through facilitating accessibility of repair factors at damaged heterochromatic regions. |
| **BARD1**  | Forms a heterodimer with BRCA1, stabilizing it and enhancing its E3 ubiquitin ligase activity essential for HR signaling and repair. |
| **BRCA1**  | Orchestrates HR by promoting DNA end resection and recruiting PALB2-BRCA2-RAD51 to DNA damage sites. |
| **BRCA2**  | Directly loads RAD51 onto single-stranded DNA at resected DSBs to initiate strand invasion and homologous pairing. |
| **CHEK1**  | A checkpoint kinase downstream of ATR that regulates cell cycle arrest and supports HR by stabilizing replication forks. |
| **CHEK2**  | Acts downstream of ATM to mediate cell cycle arrest and repair initiation, with some role in HR signaling. |
| **MRE11**  | Part of the MRN complex, initiates DNA end resection, a critical first step in HR repair of DSBs. |
| **NBN**    | Regulatory component of the MRN complex, helps recruit ATM and coordinate DNA damage signaling and resection. |
| **PALB2**  | Connects BRCA1 and BRCA2, acting as a scaffold that recruits BRCA2 and RAD51 to DNA damage sites for HR. |
| **RAD21**  | A cohesin subunit that maintains sister chromatid cohesion, facilitating the template alignment necessary for HR. |
| **RAD50**  | Structural component of the MRN complex, tethers DNA ends and cooperates in resection and HR initiation. |
| **RAD51**  | Central recombinase that mediates strand invasion and homologous pairing during HR. |
| **RAD51B** | A RAD51 paralog that forms complexes aiding in RAD51 filament stabilization and HR efficiency. |
| **RAD51C** | Forms complexes with other RAD51 paralogs and is essential for RAD51 filament formation and resolution of HR intermediates. |
| **RAD51D** | Participates in RAD51 paralog complexes, contributing to RAD51 filament assembly and strand invasion during HR. |
| **RAD52**  | Mediates annealing of complementary DNA strands and serves as a backup to BRCA2 in RAD51 loading, especially in BRCA-deficient cells. |
| **RAD54L** | A DNA-dependent ATPase that promotes branch migration and chromatin remodeling during late stages of HR. |
| **WRN**    | A RecQ helicase that facilitates DNA end processing and resolution of recombination intermediates, ensuring HR fidelity. |



