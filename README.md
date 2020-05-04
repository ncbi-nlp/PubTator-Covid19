# PubTator collections on COVID-19

[Pubtator](https://www.ncbi.nlm.nih.gov/research/pubtator/) provides annotations of several biomedical entities in scientific publications related to COVID-19 and SARS-CoV-2. Articles are automatically annotated with six entity types: gene/protein, drug/chemical, disease, cell type, species and genomic variants. Annotated articles are provided in BioC JSON, BioC XML and PubTator formats.

## LitCovid
[LitCovid](https://www.ncbi.nlm.nih.gov/research/coronavirus/) is a curated literature hub for tracking up-to-date scientific information about SARS-CoV-2 and COVID-19. It is the most comprehensive resource on the subject, with new articles from PubMed and PubMed Central added daily. PubTator annotations for LitCovid are updated once per day, and can be downloaded at ftp://ftp.ncbi.nlm.nih.gov/pub/lu/LitCovid/. 

## CORD-19
[CORD-19](https://pages.semanticscholar.org/coronavirus-research), the COVID-19 Open Research Dataset is (description) and privided by the [Allen Institute](https://alleninstitute.org/). PubTator annotations for CORD-19 are updated weekly, and can be downloaded at ftp://ftp.ncbi.nlm.nih.gov/pub/lu/CORD19/.

## PubTator
PubTator (description: entity types and tools used, links to web pages).

## References
[1] Chen, Q., Allot, A., & Lu, Z. (2020). Keep up with the latest coronavirus research. Nature, 579(7798), 193. doi: 10.1038/d41586-020-00694-1
[2] Comeau, D. C., Wei, C. H., Islamaj, R., & Lu, Z. (2019). PMC text mining subset in BioC: about three million full-text articles and growing. Bioinformatics, 35(18), 3533-3535. btz070.
[3] Wei, C. H., Allot, A., Leaman, R., & Lu, Z. (2019). PubTator central: automated concept annotation for biomedical full text articles. Nucleic acids research, 47(W1), W587-W593. doi: 10.1093/nar/gkz389

## License

This dataset was derived from the CORD-19 dataset, and therefore consists of two subsets, having different licenses, that are intermingled in the CORD-19-on-FHIR dataset:

- the CORD-19 dataset, subject to the CORD-19 license; and

- semantic annotations that were added by CORD-19-on-FHIR data mining, subject to a CC0 license.
 
See [LICENSE](https://github.com/fhircat/CORD-19-on-FHIR/blob/master/LICENSE).  By downloading this dataset you are agreeing to the [dataset licenses](https://github.com/fhircat/CORD-19-on-FHIR/blob/master/LICENSE).

Specific licensing information for individual articles in the dataset is available in the [metadata file](https://ai2-semanticscholar-cord-19.s3-us-west-2.amazonaws.com/2020-03-13/all_sources_metadata_2020-03-13.csv).  See also the [readme for the metadata file](https://ai2-semanticscholar-cord-19.s3-us-west-2.amazonaws.com/2020-03-13/all_sources_metadata_2020-03-13.readme).

- semantic annotations that were added by Pubtator from public domain, using the following public domain notice


```text
# ===========================================================================
#
#                            PUBLIC DOMAIN NOTICE
#               National Center for Biotechnology Information
#
#  This software/database is a "United States Government Work" under the
#  terms of the United States Copyright Act.  It was written as part of
#  the author's official duties as a United States Government employee and
#  thus cannot be copyrighted.  This software/database is freely available
#  to the public for use. The National Library of Medicine and the U.S.
#  Government have not placed any restriction on its use or reproduction.
#
#  Although all reasonable efforts have been taken to ensure the accuracy
#  and reliability of the software and data, the NLM and the U.S.
#  Government do not and cannot warrant the performance or results that
#  may be obtained by using this software or data. The NLM and the U.S.
#  Government disclaim all warranties, express or implied, including
#  warranties of performance, merchantability or fitness for any particular
#  purpose.
===============================================================================
 
 
```
