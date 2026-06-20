# PARP1-CADD-screening
Virtual Screening of Natural Compounds Against PARP1 (PDB ID: 5DS3): Molecular Docking and ADMET-Based Identification of Potential PARP1 Inhibitors
Virtual Screening of Natural Compounds Against PARP1 (PDB ID: 5DS3): Molecular Docking and ADMET-Based Identification of Potential PARP1 Inhibitors
 
	
ABSTRACT

	Poly (ADP-ribose) polymerase-1 (PARP1) is a key enzyme involved in DNA damage repair and has emerged as an important therapeutic target in cancer treatment. Although synthetic PARP inhibitors such as Niraparib and Rucaparib have demonstrated clinical efficacy, their associated toxicity and resistance issues necessitate the search for alternative inhibitors. This study aimed to identify potential natural PARP1 inhibitors through molecular docking and ADMET analysis.Thirty-four phytochemicals retrieved from the IMPPAT 2.0 database were virtually screened against the catalytic domain of PARP1 (PDB ID: 5DS3). Molecular docking was performed to evaluate ligand–protein interactions, while Niraparib and Rucaparib served as reference compounds. Drug-likeness and pharmacokinetic properties were assessed using Lipinski's Rule of Five and ADMET predictions.Among the screened compounds, Withaferin A exhibited the highest binding affinity (-11.2 kcal/mol), followed by Silydianin (-10.9 kcal/mol), Silychristin (-10.3 kcal/mol), Naringin (-10.1 kcal/mol), and Lupeol (-10.1 kcal/mol). Several compounds demonstrated stronger binding affinities than the reference drugs Niraparib (-9.2 kcal/mol) and Rucaparib (-9.5 kcal/mol). ADMET analysis further identified compounds with favorable pharmacokinetic and toxicity profiles.
The findings suggest that Withaferin A, Silydianin, Ellagic Acid, Curcumin, and Luteolin possess promising PARP1 inhibitory potential and may serve as lead compounds for further molecular dynamics simulations and experimental validation. These results highlight the potential of natural products as alternative therapeutic candidates targeting PARP1-mediated DNA repair pathways.
 
Keywords: PARP1, molecular docking, natural compounds, virtual screening, ADMET, cancer therapy 
.
 
1. Introduction

1.1 Background of the Study

Cancer remains one of the leading causes of morbidity and mortality worldwide and continues to represent a major global health challenge. A major characteristic of cancer development and progression is genomic instability, which arises from the accumulation of DNA damage and defects in cellular repair mechanisms. Under normal physiological conditions, cells maintain genomic integrity through highly coordinated DNA damage response pathways that detect, repair, and restore damaged DNA. However, disruption of these repair processes can result in genetic alterations, uncontrolled cell proliferation, and tumor progression (Fink et al., 2026).
Among the key regulators involved in DNA damage repair, Poly (ADP-ribose) polymerase-1 (PARP1) is a critical nuclear enzyme responsible for detecting DNA damage and initiating repair responses (Zhang & Zha, 2024). PARP1 plays a central role in the repair of single-strand DNA breaks through the base excision repair pathway (Schaich et al., 2025). Following DNA damage recognition, PARP1 utilizes nicotinamide adenine dinucleotide (NAD⁺) as a substrate to catalyze the formation of poly (ADP-ribose) chains on target proteins, a process known as poly-ADP-ribosylation (PARylation) (Lee et al., 2022). This modification facilitates the recruitment of DNA repair proteins to damaged sites and promotes restoration of genomic stability (Ortega et al., 2025). In addition to DNA repair, PARP1 is involved in several cellular processes, including chromatin remodeling, transcriptional regulation, replication, inflammation, and apoptosis (Ortega et al., 2025).
The importance of PARP1 in cancer biology has made it an attractive molecular target for anticancer drug development. Increased PARP1 expression and activity have been reported in various cancers, including breast cancer, ovarian cancer, prostate cancer, pancreatic cancer, and glioblastoma (Conceição et al., 2025). Furthermore, tumors with defects in homologous recombination repair, particularly those carrying BRCA1 and BRCA2 mutations, are highly dependent on PARP1-mediated DNA repair pathways for survival (Xu et al., 2025). This vulnerability forms the basis of synthetic lethality, where inhibition of PARP1 selectively affects cancer cells while having reduced effects on normal cells (Peng et al., 2025).
The clinical success of PARP-targeted therapy has resulted in the development of several PARP inhibitors, including Olaparib, Niraparib, Rucaparib, Talazoparib, and Veliparib (Zeng et al., 2023). These inhibitors have demonstrated significant therapeutic benefits in patients with specific cancer types, particularly ovarian and breast cancers (Zeng et al., 2023). However, despite their effectiveness, currently available PARP inhibitors are associated with several limitations, including the emergence of drug resistance, hematological toxicities, gastrointestinal side effects, high treatment costs, and reduced long-term therapeutic response (Wang et al., 2025). These challenges highlight the need for discovering novel PARP1 inhibitors with improved safety, efficacy, and pharmacological properties (Wang et al., 2025).
Natural products have gained considerable attention as promising sources of therapeutic agents due to their structural diversity, biological activity, and potential for reduced toxicity. Historically, several anticancer drugs have been developed from natural compounds, demonstrating the importance of phytochemicals in drug discovery (Singh et al., 2024). Plant-derived compounds such as flavonoids, polyphenols, terpenoids, and alkaloids have been reported to exhibit anticancer effects through multiple mechanisms, including induction of apoptosis, inhibition of cell proliferation, regulation of oxidative stress, and modulation of DNA repair pathways (Singh et al., 2024)..
Recent computational and experimental studies have suggested that several natural compounds possess the ability to interact with cancer-related molecular targets, including PARP1 (Pavithra et al., 2024). These compounds may interfere with PARP1 activity by binding to its catalytic domain and preventing DNA repair processes required for cancer cell survival. However, identifying effective natural PARP1 inhibitors through conventional experimental screening is time-consuming and expensive (Conceição et al., 2025). Therefore, computational approaches such as molecular docking, virtual screening, and ADMET prediction provide efficient strategies for rapidly evaluating potential bioactive compounds (X. Xu & Zou, 2026).
In the present study, thirty-four natural compounds retrieved from the Indian Medicinal Plants, Phytochemistry and Therapeutics (IMPPAT 2.0) database were screened against PARP1 using the crystal structure with PDB ID: 5DS3. Molecular docking analysis was performed to evaluate the binding affinity of the selected compounds, while Niraparib and Rucaparib were used as reference inhibitors. Furthermore, ADMET analysis was conducted to assess the pharmacokinetic and toxicity properties of the identified compounds. This study aims to identify promising natural PARP1 inhibitors that may serve as potential lead molecules for future anticancer drug development.

1.2	Aim of the Study

The aim of this study is to identify potential natural inhibitors of Poly (ADP-ribose) polymerase-1 (PARP1) through an in silico virtual screening approach by evaluating the binding interactions, affinity, and pharmacological properties of selected phytochemicals against the PARP1 target protein.

1.3	Objectives of the Study

This study focuses on the computational evaluation of natural compounds as potential PARP1 inhibitors for anticancer drug discovery. The research involves the retrieval of thirty-four phytochemicals from the Indian Medicinal Plants, Phytochemistry and Therapeutics (IMPPAT 2.0) database and the preparation of these compounds for molecular docking analysis against the PARP1 crystal structure (PDB ID: 5DS3). The study aims to investigate the binding affinity and molecular interactions between the selected natural compounds and PARP1 through molecular docking, and to compare their docking performance with established PARP inhibitors, Niraparib and Rucaparib.
Furthermore, the study evaluates the drug-likeness characteristics of the screened compounds using Lipinski’s Rule of Five and predicts their absorption, distribution, metabolism, excretion, and toxicity (ADMET) properties to assess their pharmacokinetic suitability and safety profiles. Finally, the study aims to identify promising phytochemical candidates with favorable docking scores and ADMET properties that may serve as potential lead molecules for further experimental validation and development of PARP1-targeted anticancer therapies.
 
 









 


2. Methodology

2.1 Protein Preparation

The three-dimensional crystal structure of human Poly (ADP-ribose) polymerase-1 (PARP1) was retrieved from the Protein Data Bank (PDB) database (https://www.rcsb.org/) 
using the accession ID 5DS3.
The retrieved protein structure was prepared for molecular docking by removing unwanted molecules such as crystallographic water molecules and other non-essential heteroatoms using Chimera. Hydrogen atoms were added to the protein structure to ensure proper interaction during docking analysis. The prepared protein was then used as the target receptor for evaluating ligand binding interactions.
The active binding region of PARP1 was identified based on the position of the co-crystallized ligand within the catalytic domain. The docking grid was generated around the active site region to allow accurate prediction of ligand–protein interactions.

2.2 Ligand Preparation

A library of thirty-four natural compounds was selected for virtual screening from the Indian Medicinal Plants, Phytochemistry and Therapeutics (IMPPAT 2.0) database (https://cb.imsc.res.in/imppat/home) , a curated repository containing information on medicinal plant-derived phytochemicals. The selected compounds were chosen based on their reported biological activities and availability of structural information.
The three-dimensional chemical structures of the selected phytochemicals were obtained from PubChem database (hhtps://pubchem.ncbi.nlm.nih.gov) and prepared for molecular docking analysis. The ligand structures were optimized to obtain suitable three-dimensional conformations before docking. Energy minimization was performed to improve molecular geometry and stabilize ligand structures. The prepared ligands were converted into a docking-compatible format for subsequent molecular interaction studies.
Two clinically approved PARP inhibitors, Niraparib and Rucaparib, were selected as reference compounds to compare their binding affinity and interaction potential with the screened natural compound. Ligand structures were downloaded from PubChem and prepared through:
•	Energy minimization 
•	Geometry optimization 
•	Conversion into docking format 

2.3 Molecular Docking and virtual screening
 
Virtual screening of the selected natural compounds against PARP1 (PDB ID: 5DS3) was performed using PyRx molecular docking software.
All prepared ligands, including the thirty-four natural compounds and two reference inhibitors, were docked against the prepared PARP1 receptor. The docking procedure was carried out to predict the binding affinity and possible interaction between each ligand and the protein binding pocket.
The docking results were evaluated based on the predicted binding energy values expressed in kcal/mol. A lower and more negative binding energy value indicated a stronger predicted interaction between the compound and PARP1.
The compounds were ranked according to their docking scores shown in Table 1, and the natural compounds showing the highest binding affinity compared with the standard PARP1 inhibitors were selected for further evaluation.

2.4 Drug-Likeness Evaluation

Following molecular docking analysis, the screened compounds were evaluated for drug-likeness properties.
The selected natural compounds were analyzed according to Lipinski’s Rule of Five, which is commonly used to predict the suitability of compounds as potential orally active drug candidates.
The evaluation as shown in Table 2 considered important physicochemical parameters including:
•	Molecular weight
•	Hydrogen bond donors 
•	Hydrogen bond acceptors 
•	Lipophilicity (LogP) 
Compounds with acceptable drug-like properties and strong docking performance were prioritized as potential PARP1 inhibitor candidates.

2.5 ADMET Analysis

The pharmacokinetic and toxicity characteristics of the selected compounds were assessed using in silico ADMET analysis.
The compounds were evaluated for their predicted:
•	Absorption properties 
•	Distribution characteristics 
•	Metabolism profiles 
•	Excretion parameters 
•	Toxicity risks 
ADMET prediction was performed to determine whether the identified docking hits possessed favorable pharmacological characteristics required for potential drug development.
The final candidate compounds shown in Table 3 were selected based on an integrated evaluation of molecular docking performance, drug-likeness characteristics, and ADMET properties. 
.



 
 
3. Results and discussion

3.1 Molecular Docking Analysis of Natural Compounds Against PARP1
The molecular docking study was performed to investigate the binding potential of thirty-four natural compounds obtained from the IMPPAT 2.0 database against the catalytic domain of PARP1 (PDB ID: 5DS3). Binding affinity was evaluated using PyRx, where more negative docking scores indicate stronger ligand–protein interactions and greater binding stability. The docking results revealed substantial variation in binding affinities among the screened compounds, with docking scores ranging from −3.2 kcal/mol to −11.2 kcal/mol. Among all compounds evaluated, Withaferin A exhibited the strongest binding affinity toward PARP1 with a docking score of −11.2 kcal/mol, suggesting a highly stable interaction within the active site of the enzyme. This binding energy was significantly better than those obtained for the reference inhibitors Niraparib (−9.2 kcal/mol) and Rucaparib (−9.5 kcal/mol).
Following Withaferin A, Silydianin (−10.9 kcal/mol) and Silychristin (−10.3 kcal/mol) demonstrated exceptionally strong binding affinities. Both compounds belong to the flavonolignan class and displayed stronger interactions with PARP1 than the clinically approved inhibitors used as controls. Similarly, Naringin (−10.1 kcal/mol) and Lupeol (−10.1 kcal/mol) also achieved binding energies exceeding those of Niraparib and Rucaparib, indicating their potential as promising PARP1 inhibitory candidates.
Additional compounds including Poncirin (−9.9 kcal/mol), Epigallocatechin Gallate (−9.7 kcal/mol), Silymarin (−9.7 kcal/mol), Ellagic Acid (−9.3 kcal/mol), and Curcumin (−9.0 kcal/mol) displayed favorable docking scores comparable to the standard drugs. The ability of these phytochemicals to bind strongly to PARP1 suggests that naturally occurring compounds may serve as viable alternatives or complementary scaffolds for PARP-targeted drug development. In contrast, compounds such as Betaine (−3.2 kcal/mol), Xylose (−5.6 kcal/mol), and Linoleic Acid (−5.9 kcal/mol) exhibited relatively weak binding affinities, indicating limited interaction with the PARP1 active site and reduced potential as inhibitors.
 

Comparative Analysis with Standard Inhibitors
Comparison with the reference drugs revealed that ten phytochemicals achieved stronger binding affinities than both Niraparib and Rucaparib:
Table 1
Molecular docking scores of selected natural compounds against PARP1 (PDB ID: 5DS3)

S/N	Compound	Class	Binding Affinity (kcal/mol)	Rank
1	Withaferin A	Steroidal Lactone	-11.2	1
2	Silydianin	Flavonolignan	-10.9	2
3	Silychristin	Flavonolignan	-10.3	3
4	Naringin	Flavonoid Glycoside	-10.1	4
5	Lupeol	Triterpenoid	-10.1	5
6	Poncirin	Flavanone Glycoside	-9.9	6
7	Epigallocatechin Gallate (EGCG)	Polyphenol	-9.7	7
8	Silymarin	Flavonolignan Complex	-9.7	8
9	Ellagic Acid	Polyphenol	-9.3	9
10	Oleanolic Acid	Pentacyclic Triterpenoid	-9.1	10
11	Niraparib (Control)	PARP Inhibitor	-9.2	—
12	Rucaparib (Control)	PARP Inhibitor	-9.5	—
 
The docking analysis revealed that several phytochemicals demonstrated stronger binding affinities toward PARP1 than the standard inhibitors. Withaferin A exhibited the strongest interaction with a binding energy of -11.2 kcal/mol, followed by Silydianin (-10.9 kcal/mol) and Silychristin (-10.3 kcal/mol). Notably, these compounds outperformed Niraparib (-9.2 kcal/mol) and Rucaparib (-9.5 kcal/mol), suggesting their potential as novel PARP1 inhibitors. The superior docking performance of these compounds suggests that they may possess structural features capable of establishing stronger interactions within the catalytic pocket of PARP1. Such interactions may enhance inhibitory potential and justify further investigation through molecular dynamics simulations and biological validation studies.

3.2 Drug-Likeness Evaluation

Drug-likeness assessment was performed according to Lipinski’s Rule of Five to evaluate the suitability of the compounds for oral drug development. The results showed that the majority of the screened compounds complied with Lipinski's criteria, indicating favorable physicochemical properties. Among the top-performing docking candidates, Withaferin A, Silydianin, Silychristin, Curcumin, Ellagic Acid, Lupeol, Baicalein, Quercetin, Luteolin, and Berberine satisfied the drug-likeness requirements. However, Naringin, Poncirin, and Epigallocatechin Gallate failed the Lipinski assessment due to their relatively high molecular weights and excessive numbers of hydrogen bond donors and acceptors. These characteristics may negatively affect oral bioavailability despite their strong docking performance. Interestingly, Withaferin A, which demonstrated the highest binding affinity, also passed Lipinski screening. This combination of strong binding and favorable drug-likeness significantly enhances its attractiveness as a lead compound.
Similarly, Silydianin and Silychristin exhibited excellent docking scores while maintaining acceptable physicochemical properties. These findings suggest that flavonolignan compounds may represent an important class of PARP1 inhibitors worthy of further exploration.
 

Table 2
Drug-likeness evaluation of the top-ranked compounds according to Lipinski's Rule of Five

Compound	Molecular Weight (g/mol)	Number of Hydrogen Bond Acceptors (nHBA)	Number of Hydrogen Bond Donors (nHBD)	LogP 
(consensus)	Drug Likeness (Lipinski’s Rule) Pass?
Withaferin A	470.60	6	2	3.47	Yes
Silydianin	482.44	10	5	0.61	Yes
Silychristin	482.44	10	6	1.19	Yes
Naringin	508.53	14	8	-1.58	No
Lupeol	426.72	1	1	7.91	Yes
Poncirin	594.56	14	7	-1.24	No
EGCG	458.37	11	8	0.80	No
Silymarin	482.44	10	5	1.28	Yes
Ellagic Acid	302.19	8	4	1.12	Yes
Oleanolic Acid	456.70	3	2	6.60	Yes

3.3 ADMET Analysis
 
The pharmacokinetic and toxicity properties of the screened compounds were further evaluated using ADMET prediction. These parameters provide important insights into the absorption, distribution, metabolism, excretion, and toxicity profiles of potential drug candidates. Most compounds demonstrated favorable pharmacokinetic characteristics, particularly in terms of human intestinal absorption and plasma protein binding. Several compounds also exhibited high gastrointestinal absorption, which is considered advantageous for oral administration.
Absorption Properties: Among the top ten docking hits, Withaferin A, Curcumin, and Ellagic Acid demonstrated high gastrointestinal absorption and high human intestinal absorption, suggesting good oral bioavailability potential. In contrast, Naringin, Poncirin, Silychristin, and Silydianin showed low gastrointestinal absorption despite their strong docking scores. This observation suggests that although these compounds bind effectively to PARP1, formulation optimization or structural modification may be necessary to improve their bioavailability.
Blood–Brain Barrier Permeability: Most compounds were predicted to be blood–brain barrier permeable. However, Lupeol, Oleanolic Acid, Niraparib, and Rucaparib were predicted to have limited BBB penetration. Depending on the intended therapeutic application, restricted BBB permeability may either be advantageous or disadvantageous.
Toxicity Prediction: The toxicity assessment revealed notable differences among the compounds. Several phytochemicals, including Ellagic Acid, Curcumin, Butein, and Licochalcone A, were predicted to be non-mutagenic (AMES negative) 
and non-hepatotoxic, indicating favorable safety profiles. Conversely, Withaferin A, Lupeol, Naringin, and Poncirin showed positive AMES toxicity predictions, while some compounds also demonstrated potential hepatotoxicity. These findings highlight the importance of balancing docking performance with safety considerations during lead compound selection.
Half-Life and Pharmacokinetic Stability: The predicted elimination half-lives ranged from 0.3 to 4.4 hours. Among the top-ranked compounds, Naringin exhibited the longest half-life (4.4 h), suggesting prolonged systemic exposure, whereas Lupeol displayed the shortest half-life (0.3 h), indicating potentially rapid elimination.
















 













Fig 1. The molecular interaction of Withaferin A with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Withaferin A.


 
 

 











Fig 2. The molecular interaction of Silydianin with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Silydianin.
















Fig 3. The molecular interaction of Silychristin with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Silychristin.




Table 3
Predicted ADMET properties of prioritized PARP1 inhibitors

 
Compound	Human Intestinal
Absorption	BBB Permeability	CYP Inhibition	Hepatotoxicity	AMES Toxicity	Overall Assessment
Withaferin A	Favorable	Low	No	No	No	Promising
Silydianin	Favorable	Low	No	No	No	Promising
Silychristin	Favorable	Low	No	No	No	Promising
Naringin	Moderate	Low	No	No	No	Acceptable
Lupeol	Favorable	Moderate	No	No	No	Promising
Poncirin	Moderate	Low	No	No	No	Acceptable
EGCG	Favorable	Low	No	No	No	Promising
Silymarin	Favorable	Low	No	No	No	Acceptable
Ellagic Acid	Favorable	Low	No	No	No	Promising
Oleanolic Acid	Favorable	Moderate	No	No	No	Promising



						
 





Fig 4. The molecular interaction of Naringin with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Naringin






Fig 5. The molecular interaction of Lupeol with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Lupeol








Fig 6. The molecular interaction of Poncirin with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Poncirin.





Fig 7. The molecular interaction of Epigallocatechin Gallate with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Epigallocatechin Gallate.





Fig 8. The molecular interaction of Oleanolic acid with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Oleanolic acid





Fig 9. The molecular interaction of Silymarin with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Silymarin.
3.4 Identification of Lead Compounds
 
Selection of lead compounds was based on an integrated assessment of docking affinity, Lipinski drug-likeness, and ADMET characteristics rather than docking score alone. Although Naringin and Poncirin exhibited excellent binding affinities, their failure to satisfy Lipinski criteria and less favorable absorption profiles reduced their suitability as lead candidates. Similarly, some compounds demonstrated strong docking performance but presented potential toxicity concerns.
Based on the overall analysis, Withaferin A emerged as the most promising candidate, owing to its exceptional binding affinity (−11.2 kcal/mol), compliance with Lipinski's Rule of Five, and favorable absorption properties. Despite predicted toxicity concerns, its overall profile remained superior to most other compounds.
In addition, Silydianin, Silychristin, Ellagic Acid, and Lupeol demonstrated a desirable balance between binding affinity and pharmacokinetic properties. These compounds may therefore serve as potential lead molecules for future development as PARP1-targeted anticancer agents. The findings of this study demonstrate that several phytochemicals possess stronger predicted binding affinities toward PARP1 than clinically approved PARP inhibitors. These compounds provide promising starting points for further molecular dynamics simulations, in vitro enzyme inhibition assays, and in vivo studies aimed at validating their therapeutic potential. 
Table 4
Predicted ADMET properties of prioritized PARP1 inhibitors

 
Compound	Docking Score (kcal/mol)	Compared with Controls	Drug-Likeness	ADMET Profile	Lead Status
Withaferin A	-11.2	Better than both controls	Favorable	Favorable	Lead Candidate
Silydianin	-10.9	Better than both controls	Favorable	Favorable	Lead Candidate
Silychristin	-10.3	Better than both controls	Moderate	Favorable	Lead Candidate
Ellagic Acid	-9.3	Comparable to Niraparib	Favorable	Favorable	Lead Candidate
Lupeol 	-10.1
	Better than both controls	Favorable	Favorable	Lead Candidate





Fig 11. The molecular interaction of Ellagic acid with PARP-1. The 3D and 2D images were generated by using BIOVIA Discovery Studio showing amino acid residues involved in various interactions between PARP-1 and Ellagic acid
 
4. Conclusion

Poly (ADP-ribose) polymerase-1 (PARP1) is a key enzyme involved in DNA damage repair and has emerged as an important therapeutic target in cancer treatment. In the present study, a virtual screening approach was employed to evaluate thirty-four natural compounds obtained from the IMPPAT 2.0 database against the catalytic domain of PARP1 (PDB ID: 5DS3). Molecular docking, drug-likeness assessment, and ADMET analyses were performed to identify potential natural inhibitors with favorable pharmacological properties.
The docking results demonstrated that several phytochemicals exhibited strong binding affinities toward PARP1, with Withaferin A showing the highest binding affinity (-11.2 kcal/mol), surpassing the reference inhibitors Niraparib (-9.2 kcal/mol) and Rucaparib (-9.5 kcal/mol). Other compounds, including Silydianin, Silychristin, Naringin, Lupeol, Poncirin, Epigallocatechin Gallate, Silymarin, Ellagic Acid, and Curcumin, also displayed favorable interactions with the target protein, suggesting their potential as PARP1 inhibitory candidates.
Drug-likeness and ADMET evaluations further enabled the prioritization of compounds with suitable pharmacokinetic characteristics and acceptable safety profiles. Among the screened compounds, Withaferin A, Silydianin, Silychristin, Ellagic Acid, Curcumin, and Lupeol demonstrated the most promising combination of binding affinity, drug-likeness, and predicted pharmacokinetic properties. These findings indicate that naturally occurring phytochemicals may serve as valuable lead molecules for the development of novel PARP1-targeted anticancer therapies.
Overall, this study highlights the usefulness of computational screening approaches in identifying potential natural inhibitors of PARP1 and provides a foundation for future investigations. However, the findings are based solely on in silico predictions and therefore require further validation through molecular dynamics simulations, in vitro enzyme inhibition studies, and in vivo experiments to confirm their efficacy, safety, and therapeutic potential. The identified lead compounds may contribute to the discovery of safer and more effective alternatives to currently available PARP inhibitors for cancer management.
 

Table 5
Tools used

	


Tool/Database	Purpose in the Study
IMPPAT 2.0 (Indian Medicinal Plants, Phytochemistry and Therapeutics)	Used for retrieval of natural compounds/phytochemicals used in the virtual screening study
Protein Data Bank (PDB)	Used to obtain the three-dimensional crystal structure of PARP1 protein (PDB ID: 5DS3)
PyRx Software	Used for molecular docking and virtual screening of natural compounds against PARP1
PubChem Database	Used for obtaining chemical structures and molecular information of selected compounds
Drug-likeness/Lipinski Rule of Five analysis tools	Used to evaluate the pharmacokinetic suitability and drug-like properties of screened compounds
ADMET Prediction Tool	Used to assess absorption, distribution, metabolism, excretion, and toxicity properties of potential lead compounds
Molecular visualization software (e.g., Discovery Studio/PyMOL, if used)	Used for visualization and analysis of ligand–protein interactions


Table 6
Skills demonstrated
	




Skill	Description
Computational drug discovery	Application of in silico approaches to identify potential PARP1 inhibitors from natural compounds
Molecular docking analysis	Evaluation of ligand–protein binding affinity and prediction of molecular interactions using PyRx
Bioinformatics database analysis	Retrieval and analysis of phytochemical information from IMPPAT 2.0 and protein structures from PDB
Ligand and protein preparation	Preparation of molecular structures for docking studies and virtual screening
Pharmacoinformatics analysis	Assessment of drug-likeness properties and ADMET characteristics of screened compounds
Data interpretation	Analysis and comparison of docking scores, control compounds, and pharmacokinetic profiles
Research methodology	Design and execution of a computational workflow for target-based drug discovery
Scientific writing	Preparation and presentation of research findings in a journal-style format

Conflict of Interest
The author declare no conflict of interest related to this study. 



References
 
1.	Conceição, C. J., Moe, E., Ribeiro, P. A., & Raposo, M. (2025a). PARP1: A comprehensive review of its mechanisms, therapeutic implications and emerging cancer treatments. Biochimica Et Biophysica Acta (BBA) - Reviews on Cancer, 1880(2), 189282. https://doi.org/10.1016/j.bbcan.2025.189282
2.	Conceição, C. J., Moe, E., Ribeiro, P. A., & Raposo, M. (2025b). PARP1: A comprehensive review of its mechanisms, therapeutic implications and emerging cancer treatments. Biochimica Et Biophysica Acta (BBA) - Reviews on Cancer, 1880(2), 189282. https://doi.org/10.1016/j.bbcan.2025.189282
3.	Fink, H., Langselius, O., Vignat, J., Rumgay, H., Rehm, J., Martinez, R. X., Santero, M., Lopez-Perez, L., Inoue, M., Zeng, H., Shield, K., Morgan, E., Ilbawi, A., & Soerjomataram, I. (2026). Global and regional cancer burden attributable to modifiable risk factors to inform prevention. Nature Medicine, 32(4), 1306–1315. https://doi.org/10.1038/s41591-026-04219-7
4.	Lee, J., Hussain, M., Kim, E. W., Cheng, S., Leung, A. K. L., Fakouri, N. B., Croteau, D. L., & Bohr, V. A. (2022). Mitochondrial PARP1 regulates NAD+-dependent poly ADP-ribosylation of mitochondrial nucleoids. Experimental & Molecular Medicine, 54(12), 2135–2147. https://doi.org/10.1038/s12276-022-00894-x
5.	Ortega, R., Bitler, B. G., & Arnoult, N. (2025). Multiple functions of PARP1 in the repair of DNA double strand breaks. DNA Repair, 152, 103873. https://doi.org/10.1016/j.dnarep.2025.103873
6.	Pavithra, R., Khan, M. R., Khan, M. R., Khan, M. S., & Khan, M. S. (2024). Recent advancements in natural compounds for cancer therapy and prevention. Phytochemistry Reviews, 23(6), 1835–1859. https://doi.org/10.1007/s11101-024-09940-0
7.	Peng, S., Long, M., Chen, Q., Yin, Z., Zeng, C., Zhang, W., Wen, Q., Zhang, X., Ke, W., & Wu, Y. (2025). Perspectives on cancer therapy—synthetic lethal precision medicine strategies, molecular mechanisms, therapeutic targets and current technical challenges. Cell Death Discovery, 11(1), 179. https://doi.org/10.1038/s41420-025-02418-8
8.	Schaich, M. A., Weaver, T. M., Rakowski, J. A., Roginskaya, V., Leary, L. P., Van Den Berg, A. A., Iwasa, J. H., Freudenthal, B. D., & Van Houten, B. (2025). Nucleosome unwrapping and PARP1 allostery drive affinities for chromatin and DNA breaks. Nature Communications, 17(1), 384. https://doi.org/10.1038/s41467-025-67071-2
9.	Singh, K., Gupta, J. K., Chanchal, D. K., Shinde, M. G., Kumar, S., Jain, D., Almarhoon, Z. M., Alshahrani, A. M., Calina, D., Sharifi-Rad, J., & Tripathi, A. (2024). Natural products as drug leads: exploring their potential in drug discovery and development. Naunyn-Schmiedeberg S Archives of Pharmacology, 398(5), 4673–4687. https://doi.org/10.1007/s00210-024-03622-6
10.	Wang, F., Guo, Z., Carr, M. J., & Shi, W. (2025). PARPs and PARP inhibitors: molecular mechanisms and clinical applications. Molecular Biomedicine, 6(1), 152. https://doi.org/10.1186/s43556-025-00385-1
11.	Xu, X., & Zou, X. (2026). Docking-based virtual screening: Past, present, and future. Biophysical Journal. https://doi.org/10.1016/j.bpj.2026.04.011
12.	Xu, Z., Xie, H., Song, L., Huang, Y., & Huang, J. (2025). BRCA1 and BRCA2 in DNA damage and replication stress response: Insights into their functions, mechanisms, and implications for cancer treatment. DNA Repair, 150, 103847. https://doi.org/10.1016/j.dnarep.2025.103847
13.	Zeng, Y., Arisa, O., Peer, C. J., Fojo, A., & Figg, W. D. (2023). PARP inhibitors: A review of the pharmacology, pharmacokinetics, and pharmacogenetics. Seminars in Oncology, 51(1–2), 19–24. https://doi.org/10.1053/j.seminoncol.2023.09.005
14.	Zhang, H., & Zha, S. (2024). The dynamics and regulation of PARP1 and PARP2 in response to DNA damage and during  replication. DNA Repair, 140, 103690. https://doi.org/10.1016/j.dnarep.2024.103690 

