# SHACLedChess

This repository is about a data model in RDF and SHACL to allow for representation and validation of chess games.
Inspired by a <a href="https://www.linkedin.com/pulse/ontology-modeling-shacl-getting-started-holger-knublauch-iwlrf/">LinkedIn Learning</a> from Holger Knublauch it extends his models' specification and capabilities considerably.

### chess_ontology.ttl
This ontology defines all basic definitions required to represent a game of chess within the RDF.

### chess_shapes.ttl
This ontology is a collection of SHACL shapes required to validate a game of chess represented within the RDF.

### example.ttl
This ontology contains **multiple chess games** to illustrate aspects of the model i.e. a <span style="color:green">valid</span> game, another with an <span style="color:red">illegal piece position</span>
