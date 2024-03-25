# scispacy-nlp
In a nutshell, the notebook contains multiple Python functions to accomplish the following:
- Download a list of drug labels from fda.gov.
- Convert the text from PDF to JSON for use with Doccano, an open-source text annotation tool, for validation.
- Run three SciSpacy models on the extracted text for inference to extract Named Entity Recognition (NER) entities, such as drugs, diseases, and genes, from FDA drug label, then save various types of files, including entities and their positions, for validation.
