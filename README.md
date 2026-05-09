# ReqSpecOnto

A semantic web framework developed by Usman Ahmed under the supervision of Dr. Khuram Shahzad, for unambiguous Software Requirements Specification (SRS).

# Core Architecture

* Upper Ontology: A standardized schema of classes, properties, and constraints that provides a reusable framework for any software domain.

* Derived Ontology: A domain-specific implementation layer consisting of individuals (instances) validated against Fermi National Accelerator Laboratory’s Budget and Planning System (BPS).

# Technical Validation & Research
The model was rigorously validated for logical consistency and integrity using the HermiT Reasoner and verified through SPARQL data retrieval queries.

# Industry Applications & Impact

* Automated Consistency Checking: Reduces manual review time by using reasoners to identify conflicting requirements automatically.

* Interoperability: Facilitates seamless data exchange between heterogeneous Requirements Engineering (RE) tools through a shared semantic vocabulary.

* Knowledge Traceability: Enhances impact analysis by mapping dependencies across the software development lifecycle, critical for large-scale federal systems like those managed by the U.S. Department of Energy.

# Files
Project contains two files namely, ReqSpecOnto.owl & ReqSpecOnto-Fermi.owl

ReqSpecOnto.owl is the Upper generic Ontology which can be applied in other software scenarios while,

ReqSpecOnto-Fermi.owl is the use case of FermiLab applied with individuals on upper ontology as an example of usage.

