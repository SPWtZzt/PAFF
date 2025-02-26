# PAFF
PAFF: A Progression-Aware Fusion Framework on Pseudo-Paired Data for Prognostic Prediction in Hepatocellular Carcinoma 

## Abstract
Cirrhosis is a critical precursor stage of hepatocellular carcinoma (HCC). Although the pathway of progression from cirrhosis to HCC holds potential to provide valuable insights for prognostic prediction in HCC, previous studies have largely overlooked progression information. Moreover, collecting long-term follow-up paired data in clinical settings for the investigation of progression information is challenging. To address above limitations, we propose a progression-aware fusion framework (PAFF) that constructs pseudo-paired data and extracts progression information to improve prediction performance. In PAFF, an optimal transport matching strategy based on hepatic function propensity scores and latent features encoded by an autoencoder is first performed on separate cirrhosis and HCC datasets to construct pseudo-paired data. Second, progressive fusion is employed to integrate cirrhosis and HCC information deeply to form implicit progression information. Third, the implicit progression information is explicitly extracted in the proposed content-aware manner, wherein cirrhosis information serves as a query reference for progressively fused tokens. Finally, the explicit progression information is combined with imaging and clinical information to achieve prognostic prediction. This study includes over 2000 subjects in total, with 896 subjects with HCC having complete follow-up records. Moreover, PAFF is evaluated on an independent testing set to assess its robustness. PAFF represents a novel approach that leverages progression information for HCC prognostic prediction without requiring paired data. This framework not only improves prognostic performance but also introduces a new information source beyond conventional imaging and clinical information. 



## Note
The source code will be open-sourced upon manuscript acceptance.
