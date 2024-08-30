---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
page_title: Computational Biology Lab @ Duke
---
{% include image.html image_path="pics/yizhang.png" image_width="20%" %}

### Yi Zhang, Ph.D.
**Yi is an Assistant Professor at [Duke University][Duke] in the [Department of Neurosurgery][DukeNeurosurgery] and [Department of Biostatistics and Bioinformatics][DukeBB].** Yi obtained PhD in Bioengineering with [Dr. Jun S. Song][SongLab] at [University of Illinois at Urbana-Champaign][UIUC]. She joined [Dr. X. Shirley Liu][LiuLab]'s lab and with co-mentors [Dr. Myles Brown][MylesLab] and [Dr. Xihong Lin][LinLab], as a Research Fellow at [Department of Data Science, Dana-Farber Cancer Institute][DFCI] and [Harvard University School of Public Health][HSPH]. She has been developing integrative genomic methods to identify functional gene regulatory mechanisms behind disease-associated human genetic variants. She has also been developing machine learning methods that leverage large-scale single-cell datasets to understand cell states in tumor microenvironment, and also machine learning methods for spatial transcriptomics data. Ongoing work includes statistical and deep learning modeling of single-cell and spatial transcriptomics, statistical models for genetics and functional genomics, to understand heterogenous complex diseases.


{% include spareline.html%}
- **We are open in recruiting postdocs, students, and staff**. Interested in computational biology, machine learning, bioinformatics, cancer genomics, single-cell multi-omics, spatial transcriptomics, human genetics, tumor immunology, or brain tumor? - **Welcome to join us!**

{% include linebreaker.html%}

- We are interested in disease systems of multi-cellular components especially cancer. 
- We lead development of computational, statistical, and machine learning methods that leverage large-scale and multi-omic data to understand cancer initiation, progression, and therapeutic responses. 
- We foster an interdisciplinary, inclusive, and supportive environment. We welcome computational biologists, bioinformaticians, computer scientists, MDs, immunologists, and oncologists. 
- We are enthuastic collaborators to work on real-world biological and translational genomics problems. 
- <u>Postdocs</u> or PhD soon-to-be who work on computational biology, bioinformatics, cancer genomics, single-cell omics, spatial transcriptomics, machine learning, genetic variant function, and biological questions in cancer or tumor microenvironment - Welcome to contact and join us! If possible please include (1) CV or Resume (2) A short research statement describing previous/ongoing work and proposed research and interest (3) 1-3 representative publications (published, accepted, or preprint) (4) Three names of references and contact information. 
- <u>Prospective students</u> interested in our research are encouraged to apply through Duke graduate programs: Computational Biology and Bioinformatics ([CBB] - PhD), Biostatsistics (PhD & MS). Graduate admission decisions are made by program committee. MS students from Biomedical Engineering, Computer Science, ECE are welcome for research interns/assistantships. If contacting for interest, please include (1) CV or Resume and if available (2) Short description of research experience and interest (3) Three names of references. Thanks!

{% include linebreaker.html%}
---
## Research Interests
{% include spareline.html%}



{% include image.html image_path="pics/research1.png" image_width="50%" %}

Tumor, like many multi-cellular disease systems, are composed of multiple cell types. For solid tumor, the <u>Cancer-intrinsic ("Seed")</u> properties like proliferation, mutations, and epigenetic changes, and the <u>Cancer-extrinsic ("Soil")</u> properties like tumor-infiltrating immune cell states and inflammation, both affect tumor progression and therapeutic responses. We aim to understand molecular gene programs of tumor microenvironment (TME) cell states, pinpoint functional cancer-TME interactions, and identity targetable tumor immunity modulators. 

We are core members of the Brain Tumor Omics Program ([BTOP](https://neurosurgery.duke.edu/news/new-research-program-focuses-omics-better-understand-brain-tumors#:~:text=The%20Brain%20Tumor%20Omics%20Program%20(BTOP)%20addresses%20the%20issue%20of,development%20or%20influence%20therapy%20response.)) at Duke Preston Robert Tisch Brain Tumor Center. We will use our computational expertise to develop methods that allow us to understand the incurable tumor types and to improve cancer therapy efficacy. 

<u>Related work</u>: [MetaTiME for TME cell states](https://www.nature.com/articles/s41467-023-38333-8) ( *Zhang et al. Nature communications* 2023); [Low-grade glioma variant](https://academic.oup.com/neuro-oncology/article/23/4/638/5948532) (*Manjunath et al. Neuro-Oncology*, Song Lab, UIUC).
<u>Ongoing</u>: (1) Brain & Breast tumor intrinsic and extrinsic cell states; (2) Tumor-infiltrating macrophage states; (3) Spatial transcriptomics for brain tumor.



{% include linebreaker.html%}
{% include spareline.html%}


{% include image.html image_path="pics/research2.png" image_width="50%" %}

Single-cell genomics data provide high-dimensional measurement of gene expression for each cell. *How do we mathematically describe a cell? How do we find cell types or cell states most relavant to biology? How do we integrate the power of the large number of cell data points to understand what roles each cells are playing in tumors?* We develop computational methods leveraging machine learning models, large-scale single-cell genomics data, and multi-omic datatypes like spatial transcriptomics and multiome. Currently, we are particular interested in low-dimensional methods and deep learning models with interpretability. 

<u>Related work</u>: [STHD: machine learning model for high-resolution spatial transcriptomics](https://www.biorxiv.org/content/10.1101/2024.06.20.599803v1) (Sun* and Zhang*#, BioRxiv 2024), *Software*: [STHD for VisiumHD](https://github.com/yi-zhang/STHD).   [MetaTiME for TME cell states](https://www.nature.com/articles/s41467-023-38333-8) ( *Zhang et al. Nature communications* 2023). *Software*: [MetaTiME cell state annotator toolkit](https://github.com/yi-zhang/MetaTiME), [Cross-cohort training pipeline](https://github.com/yi-zhang/MetaTiMEpretrain). <u>Ongoing</u>: (1) Machine learning method for large-scale single-cell transcriptomics integration & interpretation; (2) Timecourse single-cell multiome (ATAC+RNA) modeling; (3) Spatial transcriptomics. 


{% include linebreaker.html%}
{% include spareline.html%}

{% include image.html image_path="pics/research3.png" image_width="50%" %}

Human genetic variants are natural probes to investigate cell context-dependent gene regulation related to human disease. Genome-wide association studies (GWAS) identified many genetic variants associated with cancer susceptibility. *What are the molecular mechanisms behind these associations? What cell types mediate gene modulation for a certain disease trait?* Our previous computational methods integrated multiple NGS data (*Zhang et al., 2018 Bioinformatics*), and integrated eQTL, haplotype-specific expression, epigenetics, motif simulation, and 3D chromatin interactions, to identify gene regulatory effect of functional variants in enhancers ([Gene regulatory non-coding variant](https://aacrjournals.org/cancerres/article/78/7/1579/633799/Integrative-Genomic-Analysis-Predicts-Causative), *Zhang et al. 2018 Cancer Research*). We were among the first to infer cell-dependent effect of variant-associated gene regulation ([Breast variant and immune cell](https://www.frontiersin.org/articles/10.3389/fgene.2019.00754/full), *Zhang et al. 2019 Frontiers in Genetics*). We are interested in further investigate the cell-dependent effect of genetic variants by marrying GWAS summary statistics and functional genomics in ongoing work.


[DFCI]: https://ds.dfci.harvard.edu/
[HSPH]: https://www.hsph.harvard.edu/
[LiuLab]: https://liulab-dfci.github.io/
[MylesLab]: https://mylesbrownlab.dana-farber.org/
[LinLab]: https://content.sph.harvard.edu/xlin/people.html
[SongLab]: https://song.igb.illinois.edu/
[UIUC]: https://illinois.edu/
[Duke]: https://duke.edu
[DukeSoM]: https://medschool.duke.edu
[DukeNeurosurgery]: https://neurosurgery.duke.edu/news/yi-zhang-joins-duke-neurosurgery-faculty
[DukeBB]: https://biostat.duke.edu
[Contact]: mailto:yi.zhang@duke.edu
[CBB]: https://medschool.duke.edu/education/biomedical-phd-programs/computational-biology-and-bioinformatics-program

