# PubTator collections on COVID-19

[Pubtator](https://www.ncbi.nlm.nih.gov/research/pubtator/) provides automated annotations of biomedical entities in scientific publications, including the [LitCovid](https://www.ncbi.nlm.nih.gov/research/coronavirus/) and [CORD-19](https://pages.semanticscholar.org/coronavirus-research) collections on COVID-19 and SARS-CoV-2. Annotations are provided for six entity types (gene/protein, drug/chemical, disease, cell type, species and genomic variants) in three formats (BioC JSON, BioC XML and PubTator). 

## LitCovid
[LitCovid](https://www.ncbi.nlm.nih.gov/research/coronavirus/) is a curated literature hub for tracking up-to-date scientific information about SARS-CoV-2 and COVID-19 [1]. It is the most comprehensive resource on the subject, with new PubMed and PubMed Central articles added daily. PubTator annotations for LitCovid are updated once per day. Articles in the Open Access subset include the full article text; some very recent articles will only include a title and will be updated when the abstract is made available.<br/><br/>
Download PubTator annotations for LitCovid from the NCBI LitCovid FTP site: ftp://ftp.ncbi.nlm.nih.gov/pub/lu/LitCovid/

## CORD-19
[CORD-19](https://pages.semanticscholar.org/coronavirus-research), the COVID-19 Open Research Dataset, includes approximately 59,000 scholarly articles provided by the [Allen Institute](https://alleninstitute.org/) [2]. PubTator annotations for CORD-19 are updated weekly.<br/><br/>
Download the PubTator annotations for CORD-19 at the NCBI CORD-19 FTP site: ftp://ftp.ncbi.nlm.nih.gov/pub/lu/CORD19/.

## PubTator
[PubTator](https://www.ncbi.nlm.nih.gov/research/pubtator/) is a system provided by the [NCBI BioNLP group](https://www.ncbi.nlm.nih.gov/research/bionlp/) that provides automatic annotations of biomedical concepts such as genes and mutations in PubMed abstracts and PMC full-text articles [3-5]. Annotations can be viewed in a [web interface](https://www.ncbi.nlm.nih.gov/research/pubtator/) or downloaded via [RESTful API](https://www.ncbi.nlm.nih.gov/research/pubtator/api.html) or [FTP](ftp://ftp.ncbi.nlm.nih.gov/pub/lu/PubTatorCentral). Downloaded annotations are provided in BioC JSON and BioC XML formats for full-text articles [6] and in PubTator format for title and abstract, as described [here](https://www.ncbi.nlm.nih.gov/research/bionlp/APIs/format/). 

### PubTator annotations
Automated annotations for PubTator are created with automated concept recognition systems using machine learning and disambiguated with cutting-edge deep learning for improved accuracy. Concepts identified are linked to several biomedical resources:
1. Genes and proteins are annotated by the XXX system and linked to XXX.
1. Chemicals, including drugs are annotated by the XXX system and linked to XXX.
1. disease are annotated by the XXX system and linked to XXX.
1. Cell lines are annotated by the XXX system and linked to XXX.
1. Species are annotated by the XXX system and linked to XXX.
1. Genomic variants are annotated by the XXX system and linked to XXX.

## References
[1] Chen, Q., Allot, A., & Lu, Z. (2020). Keep up with the latest coronavirus research. Nature, 579(7798), 193. doi: 10.1038/d41586-020-00694-1<br/>
[2] Wang, L. L., Lo, K., Chandrasekhar, Y., Reas, R., Yang, J., Eide, D., ... & Mooney, P. (2020). CORD-19: The Covid-19 Open Research Dataset. arXiv preprint arXiv:2004.10706.<br/>
[3] Wei, C. H., Allot, A., Leaman, R., & Lu, Z. (2019). PubTator central: automated concept annotation for biomedical full text articles. Nucleic acids research, 47(W1), W587-W593. doi: 10.1093/nar/gkz389<br/>
[4] Wei, C. H., Kao, H. Y., & Lu, Z. (2013). PubTator: a web-based text mining tool for assisting biocuration. Nucleic acids research, 41(W1), W518-W522.
[5] Wei, C. H., Leaman, R., & Lu, Z. (2016). Beyond accuracy: creating interoperable and scalable text-mining web services. Bioinformatics, 32(12), 1907-1910.
[6] Comeau, D. C., Wei, C. H., Islamaj, R., & Lu, Z. (2019). PMC text mining subset in BioC: about three million full-text articles and growing. Bioinformatics, 35(18), 3533-3535. btz070.<br/>

