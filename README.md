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

-> **Identification of hub genes** Based on the network created, the hub genes are identified.


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

## Indication and Rationale

| **Indication Chosen** | **Reasons** |
|------------------------|-------------|
| **Ovarian Cancer** | - Approximately 50% of high-grade serous ovarian cancer (HGSOC) cases show defects in homologous recombination (HR) repair mechanisms.<br>- These defects primarily arise due to mutations in key HR genes, most notably **BRCA1** and **BRCA2**.<br>- Germline or somatic mutations in **BRCA1/2** are common in HGSOC. |

*Self learning: Concept of correlation*
## Correlation Overview

| **Concept** | **Explanation** |
|-------------|-----------------|
| **What is correlation?** | Correlation is a statistical measure that describes the strength and direction of a relationship between two variables. Correlations are useful for describing simple relationships among data.<br><br>Correlation determines:<br>→ Strength of relationship<br>→ Direction (positive or negative) |
| **Types** | - **Positive linear** → upward slope<br>- **Negative linear** → downward slope<br>- **No correlation** → random cloud |
| **What is Pearson correlation?** | Measures linear relationship.<br>Assumes data is continuous, normally distributed, and homoscedastic (equal variance). |
| **What is Spearman's correlation?** | Non-parametric.<br>Based on ranked data; captures monotonic (not necessarily linear) relationships. |
| **Correlation coefficient (r)** | A number between -1 and +1 indicating the degree of relationship between two variables. |
| **Positive correlation** | As one variable increases, the other tends to increase. |
| **Negative correlation** | As one variable increases, the other tends to decrease. |
| **Zero correlation** | No linear relationship. |
| **p-value** | The p-value tells you how likely it is that your observed correlation happened by chance if there were actually no real relationship. |
| **r-value** | Strength + direction of the correlation. |
| **p-value (again)** | Statistical significance of r. |
| **Correlation** | How variables move together. |
| **Pearson** | Measures linear correlation. |
| **Spearman** | Measures rank-based monotonic relationship. |
| **Causation** | A causes B (not implied by correlation!). |

*Test case : Currently we are retriving data from cbioportal and analysing the mRNA expression data of the same. For the present scenario, I am taking into consideration 5 HR genes and trying to generate the correlation matrix, p,q and a network between them.*

**STEP1 : Data retrieval from cbioportal**
-> Go to Cbioportal and type the indication name and choose the dataset to be used for further analysis
-> Click on copy link and paste it in the terminal

TERMINAL COMMAND 1: *!wget https://cbioportal-datahub.s3.amazonaws.com/ov_tcga_pan_can_atlas_2018.tar.gz*
EXPLANATION: This code uses the wget command to download a file from a specified URL. This code downloads a compressed data archive from the provided URL to the Colab environment.

TERMINAL COMMAND 2: *!tar -xvzf ov_tcga_pan_can_atlas_2018.tar.gz*
EXPLANATION: This code snippet uses the tar command to extract the contents of a gzipped tar archive that was previously downloaded.
-xvzf: These are options passed to the tar command:
x: Extract files from an archive.
v: Verbose, list files as they are extracted.
z: Decompress the archive using gzip. This option is used because the file has a .gz extension, indicating it was compressed with gzip.
f: Specify the archive file name.

In summary, this code extracts the files and directories contained within the ov_tcga_pan_can_atlas_2018.tar.gz file into the current directory. This makes the data files within the archive accessible for further processing

**STEP2: Choosing the appropriate file and loading the contents into the pandas dataframe**
-> The appropriate mRNA expression file is taken and the data from the same is being fit into the pandas dataframe for further analysis
-> File chosen in this scenario:

TERMINAL COMMAND 3: *import pandas as pd
import numpy as np
from scipy.stats import pearsonr
import scipy.stats as stats

# Path to your uploaded file
file_path = "ov_tcga_pan_can_atlas_2018/data_mrna_seq_v2_rsem.txt"

# Load the file, skipping comment lines
df = pd.read_csv(file_path, sep="\t", comment='#')* 

EXPLANATION: 
-> Imports libraries: It imports pandas (as pd) for data manipulation, numpy (as np) for numerical operations, and specific statistical functions (pearsonr and the stats module) from scipy.
-> Sets the file path: It defines the file_path variable to indicate where the data file is located.
-> Reads the data: It uses pd.read_csv() to load the data from the specified file.
-> sep="\t" tells it that columns in the file are separated by tabs.
-> comment='#' tells it to ignore lines that start with a '#' symbol.
-> The loaded data is stored in a pandas DataFrame named df.

TERMINAL COMMAND 4: df
EXPLANATION: Visualise the dataframe using command df

**STEP3: Add in the genes of interest and find the gene and sample details in relation to the gene in the dataframe**
TERMINAL COMMAND: *gene_list = ["BRCA1","BRCA2","RAD51","RAD52","RAD54L"]*
This line creates a Python list and assigns it to a variable named gene_list.
gene_list =: This assigns the list created on the right side to the variable named gene_list.
[...]: The square brackets indicate that this is a Python list.
"BRCA1","BRCA2","RAD51","RAD52","RAD54L": These are the elements of the list. Each element is a string (indicated by the quotes) representing the name of a gene. The elements are separated by commas.

**STEP4: Retrieving data specific to the gene list from the original dataframe.**

TERMINAL COMMAND 5: *df_1 = df.loc[df['Hugo_Symbol'].isin(gene_list)]*
EXPLANATION: It filters the main DataFrame (df) to keep only the rows where the 'Hugo_Symbol' is in your gene_list.
This line filters the DataFrame df to create a new DataFrame called df_1. It selects only the rows where the value in the 'Hugo_Symbol' column is present in the list of genes specified by the gene_list variable.
In essence, it's extracting the rows corresponding to the genes you are interested in from the original DataFrame.

**STEP5: Set Index**
TERMINAL COMMAND 6: *df_1 = df_1.set_index('Hugo_Symbol')*
EXPLANATION: This code snippet uses the set_index() method from the pandas library to set the 'Hugo_Symbol' column as the index of the df_1 DataFrame.
Setting the index can be useful for quickly accessing rows based on gene symbols or for aligning data with other DataFrames that share the same index.

**STEP6: Correlation analysis**
TERMINAL COMMAND 7: *df_1.T.corr()*
EXPLANATION: This code snippet calculates the pairwise Pearson correlation between the rows of the DataFrame df_1.
df_1.T: This transposes the DataFrame df_1. Since df_1 has genes as rows and samples as columns, transposing it makes samples the rows and genes the columns. This is necessary because the .corr() method calculates correlations between columns.
.corr(): This method is called on the transposed DataFrame. By default, for DataFrames of numerical data, it calculates the pairwise Pearson correlation coefficient for each pair of columns (which are now the genes from the original DataFrame).
The result is a correlation matrix where each cell (i, j) contains the Pearson correlation coefficient between gene i and gene j across all samples. This matrix can help you understand how the expression levels of the selected genes relate to each other.

Generated results:
| Hugo Symbol | BRCA1   | BRCA2   | RAD51  | RAD52  | RAD54L |
|-------------|---------|---------|--------|--------|--------|
| **BRCA1**   | 1.000   | 0.380   | 0.280  | 0.178  | 0.262  |
| **BRCA2**   | 0.380   | 1.000   | 0.456  | 0.383  | 0.493  |
| **RAD51**   | 0.280   | 0.456   | 1.000  | 0.785  | 0.872  |
| **RAD52**   | 0.178   | 0.383   | 0.785  | 1.000  | 0.812  |
| **RAD54L**  | 0.262   | 0.493   | 0.872  | 0.812  | 1.000  |

**STEP7: Generation of p and q values**

TERMINAL COMMAND 8: # Function to calculate pairwise p-values
def calculate_pvalues(df):
    df = df.dropna()._get_numeric_data()
    cols = df.columns
    pvalues_matrix = pd.DataFrame(index=cols, columns=cols)
    for i in range(len(cols)):
        for j in range(i, len(cols)):
            if i == j:
                pvalues_matrix.iloc[i, j] = 0.0
            else:
                corr, p_value = pearsonr(df[cols[i]], df[cols[j]])
                pvalues_matrix.iloc[i, j] = p_value
                pvalues_matrix.iloc[j, i] = p_value
    return pvalues_matrix

# Calculate the p-values for the correlation matrix
p_values_matrix = calculate_pvalues(df_1.T)
display(p_values_matrix)

EXPLANATION: This code snippet defines and uses a function to calculate the pairwise p-values for a given DataFrame.
calculate_pvalues(df) function:
Takes a DataFrame df as input.
df.dropna()._get_numeric_data(): This part first removes any rows with missing values (dropna()) and then selects only the numeric columns from the DataFrame (_get_numeric_data()). This is important because correlation and p-value calculations require numeric data.
cols = df.columns: Gets the names of the columns (genes in this case) after handling missing values and non-numeric data.
pvalues_matrix = pd.DataFrame(index=cols, columns=cols): Creates an empty DataFrame with the same row and column names as the numeric columns of the input DataFrame. This will store the calculated p-values.
The nested for loops iterate through all unique pairs of columns (genes).
if i == j:: If it's the same gene (diagonal of the matrix), the p-value is set to 0.0.
else: corr, p_value = pearsonr(df[cols[i]], df[cols[j]]): For different genes, it calculates the Pearson correlation coefficient (corr) and the corresponding p-value (p_value) using the pearsonr function from scipy.stats.
pvalues_matrix.iloc[i, j] = p_value and pvalues_matrix.iloc[j, i] = p_value: Stores the calculated p-value in both the upper and lower triangles of the pvalues_matrix (since the p-value for the correlation between gene A and gene B is the same as between gene B and gene A).
return pvalues_matrix: Returns the DataFrame containing the pairwise p-values.
Calculating and Displaying p-values:
p_values_matrix = calculate_pvalues(df_1.T): Calls the calculate_pvalues function with the transposed df_1 DataFrame. As explained before, we transpose df_1 so that the genes are columns for the correlation calculation.
display(p_values_matrix): Displays the resulting p-value matrix.
In summary, this code calculates the statistical significance (p-values) of the pairwise correlations between the genes in your filtered dataset. These p-values help determine if the observed correlations are statistically significant or likely due to random chance.

Generated P value table: ## P-Value Matrix

| Hugo Symbol | BRCA1    | BRCA2 | RAD51   | RAD52   | RAD54L  |
|-------------|----------|-------|---------|---------|---------|
| **BRCA1**   | 0.0      | 0.0   | 0.000001| 0.00188 | 0.000004|
| **BRCA2**   | 0.0      | 0.0   | 0.0     | 0.0     | 0.0     |
| **RAD51**   | 0.000001 | 0.0   | 0.0     | 0.0     | 0.0     |
| **RAD52**   | 0.00188  | 0.0   | 0.0     | 0.0     | 0.0     |
| **RAD54L**  | 0.000004 | 0.0   | 0.0     | 0.0     | 0.0     |

**Generation of q values**
TERMINAL COMMAND 9: from statsmodels.stats.multitest import multipletests

# Extract the p-values from the matrix and flatten them
pvalues_flat = p_values_matrix.values.flatten()

# Apply the Benjamini-Hochberg correction
reject, qvalues_flat, _, _ = multipletests(pvalues_flat, method='fdr_bh')

# Reshape the q-values back into a matrix
q_values_matrix = pd.DataFrame(qvalues_flat.reshape(p_values_matrix.shape),
                               index=p_values_matrix.index,
                               columns=p_values_matrix.columns)

display(q_values_matrix)

EXPLANATION: 
From statsmodels.stats.multitest import multipletests: This line imports the multipletests function from the statsmodels library. This function is specifically designed to apply various multiple comparison correction methods.
pvalues_flat = p_values_matrix.values.flatten():
p_values_matrix.values: This accesses the underlying NumPy array of the p_values_matrix DataFrame.
.flatten(): This method converts the 2D array of p-values into a 1D array (a single list of all p-values). Multiple comparison correction functions typically expect a flat list of p-values as input.
reject, qvalues_flat, _, _ = multipletests(pvalues_flat, method='fdr_bh'):
This is the core of the multiple comparison correction.
multipletests(pvalues_flat, method='fdr_bh'): This calls the multipletests function with your flattened list of p-values (pvalues_flat).
method='fdr_bh': This specifies the correction method to use, which is the Benjamini-Hochberg (BH) method. The BH method controls the False Discovery Rate (FDR), which is the expected proportion of rejected null hypotheses that are actually true (Type I errors).
The function returns four values:
reject: A boolean array indicating whether each corresponding p-value is rejected after correction (i.e., considered statistically significant).
qvalues_flat: The adjusted p-values, also known as q-values, in a flattened 1D array.
_, _: The other two returned values are less commonly used in this context and are assigned to _ (a convention to indicate that these values are being ignored).
q_values_matrix = pd.DataFrame(qvalues_flat.reshape(p_values_matrix.shape), index=p_values_matrix.index, columns=p_values_matrix.columns):
qvalues_flat.reshape(p_values_matrix.shape): This reshapes the flattened array of q-values back into the original matrix shape of the p_values_matrix.
pd.DataFrame(...): This creates a new pandas DataFrame from the reshaped q-values.
index=p_values_matrix.index and columns=p_values_matrix.columns: This assigns the row and column names from the original p_values_matrix to the new q_values_matrix, making it easy to see which q-value corresponds to which gene pair.
display(q_values_matrix): This displays the resulting DataFrame containing the q-values.
In summary, this code takes the raw p-values from all your pairwise gene correlation tests, adjusts them using the Benjamini-Hochberg method to account for the fact that you performed multiple tests, and then presents these adjusted p-values (q-values) in a matrix format. Q-values provide a more reliable measure of statistical significance when conducting multiple comparisons.

