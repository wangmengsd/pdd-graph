# PDD Graph： Patient-Disease-Drug Graph, Bridging MIMIC-III and Linked Data Cloud
What is PDD Graph (Patient-Disease-Drug Graph):

Electronic medical records contain multi-format electronic medical data that consist of an abundance of medical knowledge. Facing with patients symptoms, experienced caregivers make right medical decisions based on their professional knowledge that accurately grasps
relationships between symptoms, diagnosis, and treatments. We aim to capture these relationships by constructing a large and
high-quality heterogeneous graph linking patients, diseases, and drugs (PDD) in EMRs. 

Specifically, we extract important medical entities from MIMIC-III (Medical Information Mart for Intensive Care III) and automatically link them with the existing biomedical knowledge graphs, including ICD-9 ontology and DrugBank. The PDD graph presented is accessible on the Web via the SPARQL endpoint, and provides a pathway for medical discovery and applications, such as effective treatment recommendations.

A subgraph of PDD is illustrated in the followng figure to betterunderstand the PDD graph.

<div align=center> <img width="750" height="300" src="https://github.com/wangmengsd/pdd-graph/blob/master/example.png"/></div>

[Website](http://kmap.xjtudlc.com/pdd)

[DataHub URL](http://kmap.xjtudlc.com/pdd)

[Data dump](http://kmap.xjtudlc.com/pdd)

[SPARQL endpoint](http://kmap.xjtudlc.com/pdd)
