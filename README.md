# Bioinformatics_Hackathon_Group5

# Task A. Connect with your team.

Group Members: Emily Bernabe, Taylor Nutzman, Zoe Vickery, Rachel Anderson, and Julia Bertarelli

# Task B. Select a disease to study.

Sickle cell disease (SCD) is a genetic condition that affects red blood cells. Red blood cells become rigid, crescent-shaped, or "sickled," which can block blood flow and cause episodes of severe pain, known as sickle cell crises. Common symptoms include chronic anemia, fatigue, frequent infections, delayed growth in children, and episodes of intense pain in the chest, abdomen, and joints. SCD is typically diagnosed through a blood test that detects the presence of sickle-shaped cells or abnormal hemoglobin. Treatment focuses on managing symptoms and preventing complications. Painful crises are treated with hydration, pain management, and sometimes blood transfusions. Hydroxyurea, a medication that increases the production of fetal hemoglobin, can reduce the frequency of crises. In some cases, a bone marrow or stem cell transplant may offer a potential cure. Additionally, regular screenings and vaccines are recommended to prevent infections, which are common in people with SCD. Although there is no universal cure for SCD, advances in treatment have significantly improved the quality of life for many affected individuals.

# Task C. Find a gene underlying the disease.

The underlying cause of sickle cell disease is a single mutation in the β-globin gene (HBB). The mutation is a single nucleotide change, GAG to GTG, in the sixth codon of this gene. This mutation results in an amino acid change from glutamic acid to valine, which results in the production of hemoglobin S (HbS). The HBB gene is located on chromosome 11 and codes for the β-globin protein, which is an essential component of hemoglobin. In addition to HBB, other genes can modify the appearance and severity of SCD. Some of these genes include fetal hemoglobin (HbF) related genes like BCL11A, α-Thalassemia genes like HBA1 and HBA2, and inflammatory and adhesion molecule genes like VCAM1 and IL-4.

# Task D. Build a protein:protein interaction (PPI) network using the known gene protein product(s) as seeds.
![IntAct Network - HBB](https://github.com/user-attachments/assets/f2e800a5-a852-40f7-b982-84bb26ac2256)

[SickleCell gene interactions.pdf](https://github.com/user-attachments/files/17994703/SickleCell.gene.interactions.pdf)

# Task E. Find tissue-specific eQTLs DNA polymorphisms that could alter the expression of the candidate genes.
HBB eQTLs:
ENSG00000244734.4: 
chr11_6196858_A_G_b38
chr11_6189369_T_C_b38
chr11_6189365_C_A_b38
chr11_6188908_A_G_b38
chr11_6185920_C_A_b38
chr11_6185511_C_A_b38
chr11_6185478_A_G_b38
chr11_6185418_T_C_b38
chr11_6185411_G_C_b38
chr11_6183604_A_T_b38

HBG1 eQTLs:
ENSG00000213934.9:
chr11_5273171_C_T_b38
chr11_5237199_T_C_b38
chr11_5248569_A_C_b38
chr11_5270962_C_T_b38
chr11_5257923_T_C_b38
chr11_5258097_C_G_b38
chr11_5258125_C_A_b38
chr11_5262817_G_A_b38
chr11_5272395_A_T_b38
chr11_5247910_C_A_b38

HBG2 eQTLs:
ENSG00000196565.15
chr11_5259609_TA_T_b38
chr11_5256061_C_T_b38
chr11_5262780_T_C_b38
chr11_5268823_C_T_b38
chr11_5250441_C_T_b38
chr11_5261227_A_C_b38
chr11_5242453_C_T_b38
chr11_5253948_T_C_b38
chr11_5269140_C_G_b38
chr11_5253222_G_GT_b38

[b0293145-34f6-4e29-bf2f-ff9f812f450f.txt](https://github.com/user-attachments/files/17994646/b0293145-34f6-4e29-bf2f-ff9f812f450f.txt)

# Task F. Construct an hypothesis that the genes caused the disease phenotype by mechanism X.
We hypothesize that a point mutation in HBB will have a cascading effect on the phenotype of Sickle Cell Disease through mechanisms of vaso-occlusion, hemolysis, oxidative stress, and many more. Sickle cell disease is caused by a point mutation in the HBB gene, specifically an A to T substitution at the sixth codon. This results in the replacement of glutamic acid with valine in the β-globin protein (βG6V). The sickle-shaped cells are less flexible and can obstruct small blood vessels, leading to vaso-occlusion. This results in reduced blood flow and oxygen delivery to tissues, causing ischemia and pain. The altered structure of sickle cells makes them more fragile, leading to premature destruction (hemolysis). This chronic hemolysis results in anemia and the release of free hemoglobin into the plasma. The chronic stress conditions in SCD may lead to epigenetic changes and altered expression of other genes involved in inflammation, cell adhesion, and vascular function, contributing to the complex pathophysiology of the disease.

Experiment: 
1.) prep the cell culture from healthy individuals and sickle cell anemia patients. 
2.) create deoxygenated conditions for the experimental groups.
3.) Perfrom RNA sequencing to obtain a comprehensive transcriptome profile.
4.) Use existing PPI databases (BioGRID) to construct a network of proteins interacting with HBB. 
5.) Validate the key genes using qRT-PCR and Western blot analysis.
6.) Perform Gene Ontology (GO) and pathway enrichment analyses on the differentially expressed genes.
7.) In wild-type cells, use CRISPR/Cas9 to introduce the sickle cell mutation in the HBB gene.
8.) In sickle cells, use CRISPR/Cas9 to correct the mutation.
9.) Perform mass spectrometry-based proteomics on wild-type and sickle cell samples under both normal and deoxygenated conditions. Compare protein levels and post-translational modifications, focusing on the HBB PPI network.
10.) Integrate transcriptomics, proteomics, and PPI data to create a comprehensive network model.
