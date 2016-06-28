Mirrors
=======

In case files cannot be downloaded from GitHub LFS, mirrors can be found at

- https://drive.google.com/open?id=0B1kJ1OjakiU4SW8tSkVTM0NtaE0
- https://drive.google.com/open?id=0B1kJ1OjakiU4MGt3T1dMNlJ1Uk0


Data
====

* ``data.tar.gz``:

  - ``clusters.json``: dictionary of partially known clusters, in the form of 
    
    ``{cluster_id_1: [signature_id_1, ..., signature_id_N], cluster_id_2: [...], ... }``.

    Signatures from the same cluster are all known to belong to the same individual author. 
    
  - ``signatures.json``: dictionary of signature metadata, in the form of 
  
    ``{signature_id_1: {"author_name": "Doe, John", ...}, signature_id_2: {...}, ...}``
    
  - ``records.json``: dictionary of publication metadata, in the form of 
  
    ``{publication_id_1: {"title": "Lorem Ipsum", ...}, publication_id_2: {...}, ...}``
    
* ``folds.tar.gz``: 

  - ``train_signatures/train_signatures_*.json`` training folds, formatted in the same way as ``signatures.json``.
  - ``test_signatures/test_signatures_*.json`` testing folds, formatted in the same way as ``signatures.json``.

Examples of usage of these files can be found in the [Beard project](https://github.com/glouppe/beard/tree/master/examples/applications/author-disambiguation). 

Terms of use
============

This data has been extracted from the INSPIRE digital library and follows its [terms of use](http://inspirehep.net/info/general/terms-of-use). 
Datasets are provided under the CC0 license. 

Please cite this data using the following BibTex entry:

```
@article{louppe2015disambiguation,
   author = {{Louppe}, G. and {Al-Natsheh}, H. and {Susik}, M. and {Maguire}, E.},
    title = "{Ethnicity sensitive author disambiguation using semi-supervised learning}",
  journal = {ArXiv e-prints},
archivePrefix = "arXiv",
   eprint = {1508.07744},
 primaryClass = "cs.DL",
 keywords = {Computer Science - Digital Libraries, Computer Science - Information Retrieval},
     year = 2015,
    month = aug
}
```
