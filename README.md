# PubTator collections on COVID-19

[Pubtator](https://www.ncbi.nlm.nih.gov/research/pubtator/) provides automated annotations of biomedical entities in scientific publications, including the [LitCovid](https://www.ncbi.nlm.nih.gov/research/coronavirus/) and [CORD-19](https://pages.semanticscholar.org/coronavirus-research) collections on COVID-19 and SARS-CoV-2. Annotations are provided for six entity types (gene/protein, drug/chemical, disease, cell type, species and genomic variants) in two formats (BioC JSON a BioC XML). 

## LitCovid
[LitCovid](https://www.ncbi.nlm.nih.gov/research/coronavirus/) is a curated literature hub for tracking up-to-date scientific information about SARS-CoV-2 and COVID-19 [1]. It is the most comprehensive resource on SARS-CoV-2, with new PubMed and PubMed Central articles added daily. PubTator annotations for LitCovid are updated once per day. Articles in the Open Access subset include the full article text; some very recent articles will only include a title and will be updated when the abstract becomes available.<br/><br/>
Download PubTator annotations for LitCovid at https://ftp.ncbi.nlm.nih.gov/pub/lu/LitCovid/.

## CORD-19
[CORD-19](https://pages.semanticscholar.org/coronavirus-research), the COVID-19 Open Research Dataset provided by the [Allen Institute](https://alleninstitute.org/) about COVID-19 and coronavirus-related research (e.g. SARS, MERS, etc) [2]. PubTator annotations for CORD-19 are updated weekly.<br/><br/>
Download the PubTator annotations for CORD-19 at https://ftp.ncbi.nlm.nih.gov/pub/lu/CORD19/.

## PubTator
[PubTator](https://www.ncbi.nlm.nih.gov/research/pubtator/) provides automatic annotations of biomedical concepts such as genes and mutations in PubMed abstracts and PMC full-text articles [3-4]. Annotations can be viewed in a [web interface](https://www.ncbi.nlm.nih.gov/research/pubtator/) or downloaded via [RESTful API](https://www.ncbi.nlm.nih.gov/research/pubtator/api.html) or [FTP](https://ftp.ncbi.nlm.nih.gov/pub/lu/PubTatorCentral/). Downloaded annotations are provided in BioC JSON and BioC XML formats [5] (full-text articles) and in PubTator format (title and abstract), as described [here](https://www.ncbi.nlm.nih.gov/research/bionlp/APIs/format/). 

### PubTator annotations
Automated annotations for PubTator are created with automated concept recognition systems using machine learning and disambiguated with cutting-edge deep learning for improved accuracy. Concepts identified are linked to several biomedical resources:
1. __Genes and proteins__ are annotated by [GNormPlus](https://www.ncbi.nlm.nih.gov/bionlp/Tools/gnormplus) and linked to [NCBI Gene](https://www.ncbi.nlm.nih.gov/gene).
1. __Chemicals__ are annotated by a concept recognition system using [bluebert](https://github.com/ncbi-nlp/bluebert), an extension of the BERT deep learning transformer model, and linked to Medical Subject Headings ([MeSH](https://meshb.nlm.nih.gov/search)).
1. __Diseases__ are annotated by [TaggerOne](https://www.ncbi.nlm.nih.gov/bionlp/Tools/taggerone) and linked to the [MEDIC disease vocabulary](http://ctdbase.org/downloads/#alldiseases), which includes both Medical Subject Headings ([MeSH](https://meshb.nlm.nih.gov/search)) and [OMIM](https://www.omim.org/).
1. __Cell lines__ are annotated by [TaggerOne](https://www.ncbi.nlm.nih.gov/bionlp/Tools/taggerone) and linked to [Cellosaurus](https://web.expasy.org/cellosaurus/).
1. __Species__ are annotated by [SR4GN](https://www.ncbi.nlm.nih.gov/bionlp/Tools/sr4gn) and linked to [NCBI Taxonomy](https://www.ncbi.nlm.nih.gov/taxonomy).
1. __Genomic variants__ are annotated by [tmVar](https://www.ncbi.nlm.nih.gov/bionlp/Tools/tmvar) and linked to [dbSNP](https://www.ncbi.nlm.nih.gov/snp/).

## References
[1] Chen, Q., Allot, A., & Lu, Z. (2020). Keep up with the latest coronavirus research. Nature, 579(7798), 193. doi: 10.1038/d41586-020-00694-1<br/>
[2] Wang, L. L., Lo, K., Chandrasekhar, Y., Reas, R., Yang, J., Eide, D., ... & Mooney, P. (2020). CORD-19: The Covid-19 Open Research Dataset. arXiv preprint arXiv:2004.10706.<br/>
[3] Wei, C. H., Allot, A., Leaman, R., & Lu, Z. (2019). PubTator central: automated concept annotation for biomedical full text articles. Nucleic acids research, 47(W1), W587-W593. doi: 10.1093/nar/gkz389<br/>
[4] Wei, C. H., Leaman, R., & Lu, Z. (2016). Beyond accuracy: creating interoperable and scalable text-mining web services. Bioinformatics, 32(12), 1907-1910.<br/>
[5] Comeau, D. C., Wei, C. H., Islamaj, R., & Lu, Z. (2019). PMC text mining subset in BioC: about three million full-text articles and growing. Bioinformatics, 35(18), 3533-3535. btz070.<br/>

