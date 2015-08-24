Data
====

* ``data.tar.gz``:

  - ``clusters.json``: dictionary of partially known clusters, in the form of 
    
    ``{cluster_id_1: [signature_id_1, ..., signature_id_N], cluster_id_2: [...], ... }``.

    Signatures from the a same cluster are all known to belong to the same individual author. 
    
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

This data has been extracted from the INSPIRE digital library and follows its terms of use. 
Datasets are provided under the CC0 license.

http://inspirehep.net/info/general/terms-of-use
