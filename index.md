---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: Home
page_title: Computational Biology Lab @ Duke
---
{% include image.html image_path="pics/yizhang.png" image_width="20%" %}

### Yi Zhang, Ph.D.
**Starting Jan 2024, Yi is an Assistant Professor at [Duke University][Duke] in the [Department of Neurosurgery][DukeNeurosurgery] and [Department of Biostatistics and Bioinformatics][DukeBB].** Yi obtained PhD in Bioengineering with [Dr. Jun S. Song][SongLab] at [University of Illinois at Urbana-Champaign][UIUC]. She joined [Dr. X. Shirley Liu][LiuLab]'s lab and with co-mentors [Dr. Myles Brown][MylesLab] and [Dr. Xihong Lin][LinLab], as a Research Fellow at [Department of Data Science, Dana-Farber Cancer Institute][DFCI] and [Harvard University School of Public Health][HSPH]. She has been developing integrative genomic methods to identify functional gene regulatory mechanisms behind disease-associated human genetic variants. She has been developing machine learning methods that leverage large-scale single-cell datasets to understand cell states in tumor microenvironment. Her ongoing work include deep learning modeling of single-cell and spatial transcriptomics, and statistical models that combines statistical genetics and functional genomics.

{% include linebreaker.html%}
**Postdocs and Students interested in computational biology, machine learning, bioinformatics, cancer genomics, human genetics, and immunology - Welcome to join us!    [Contact]**

{% include linebreaker.html%}

- We are interested in disease systems of multi-cellular components especially cancer. 
- We lead development of computational, statistical, and machine learning methods that leverage large-scale and multi-omic data to understand cancer initiation, progression, and therapeutic responses. 
- We form an interdisciplinary, inclusive, and supportive environment. We welcome computational biologists, bioinformaticians, computer scientists, MDs, immunologists, and oncologists. 
- We are enthuastic collaborators to work on real-world biological and translational genomics problems. 
- Postdocs and students interested in computational biology, bioinformatics, cancer genomics, and machine learning - Welcome to join us! [Contact]
- Graduate programs: Computational Biology and Bioinformatics ([CBB]), Biostatsistics (PhD & MS). Incoming: University Program in Genetics and Genomics, etc.

{% include linebreaker.html%}

---
## Research Interests



{% include image.html image_path="pics/research1.png" image_width="50%" %}

We collaborate on  form  lenses to understand cancer  fascinated by disease systems with multi-cellular components, especially cancer, through the lenses of . have developed computational biology and statistical learning methods to decipher human genetic variants associated with cancer risk. I have also been developing machine learning methods for single-cell genomics data to understand cells in tumor. I also enjoy working on patient genomics data to understand disease and identify therapeutic targets. Our collaborators include Dr. Catherine J. Wu at DFCI and Dr. David E. Fisher at MGH. My research interests are to develop statistical and machine learning methods for data-driven discoveries in biomedicine. For fun, I enjoy hiking, music and wildlife photography.



{% include linebreaker.html%}

{% include image.html image_path="pics/research2.png" image_width="50%" %}

How do you mathematically describe a cell? Single-cell genomics data provide high-dimensional measurement of gene expression for each cell. How do we integrate the power of the large number of cell data points to understand what roles each cells are playing in tumors? We develop computational methods leveraging machine learning models, large-scale single-cell genomics data, and multi-omic datatypes like spatial transcriptomics and multiome. Currently, we are particular interested in low-dimensional methods and interpretable models. Related work: [MetaTiME][https://www.nature.com/articles/s41467-023-38333-8] ( *Zhang et al. Nature communications* ), topic modeling analysis for 
Interpretable machine learning methods developed for advanced integration of single-cell omics. Single-cell RNA sequencing have revealed heterogeneous cell states in the non-cancerous cells shared cross tumors. However, in analyzing tumor microenvironment (TME), canonical scRNA analysis encounters challenges of inconsistent cell states definition and difficulty in large-scale data integration. I developed a data-driven method, MetaTiME, to transfer knowledge trained from millions of single-cell data from public domain. MetaTiME learns biologically interpretable space of TME scRNA landscape, and provides a toolkit to automatically annotate cell states and evaluate signature continuums for new TME scRNA. In summary, MetaTiME utilizes interpretable machine learning to understand cellular states and gene regulators for tumor immunity and cancer immunotherapy. The software has been widely used among collaborators in automatically analyzing new tumor scRNA data and to understand tumor microenvironment heterogeneity. The computational methodology is generalizable to other systems of large-scale single-cell omics analysis.

{% include linebreaker.html%}

{% include image.html image_path="pics/research3.png" image_width="50%" %}

Human genetic variants are natural probes to investigate cell context-dependent gene regulation and human disease associations. 


[DFCI]: https://ds.dfci.harvard.edu/
[HSPH]: https://www.hsph.harvard.edu/
[LiuLab]: https://liulab-dfci.github.io/
[MylesLab]: https://mylesbrownlab.dana-farber.org/
[LinLab]: https://content.sph.harvard.edu/xlin/people.html
[SongLab]: https://song.igb.illinois.edu/
[UIUC]: https://illinois.edu/
[Duke]: https://duke.edu
[DukeSoM]: https://medschool.duke.edu
[DukeNeurosurgery]: https://neurosurgery.duke.edu
[DukeBB]: https://biostat.duke.edu
[Contact]: mailto:yi.zhang@duke.edu
[CBB]: https://medschool.duke.edu/education/biomedical-phd-programs/computational-biology-and-bioinformatics-program