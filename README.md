# Climate-System-Ontology-CSO

An ontology for Climate system that extends CCO (Common Core Ontologies) and PATO.

This is a fork of https://github.com/adavarpa/Climate-System-Ontology-CSO. The upstream
repository did not include any licensing information. This fork only reorganizes files,
adds additional documentation in this README, and future-proofs the authors deleting
the original repository.

See also original author's publication in https://www.intechopen.com/chapters/86794.

To convert the OWL file to OBO, use:

```shell
robot convert --input cso.owl --output cso.obo --check=false
```

## Common Core Ontologies

The Common Core Ontologies (CCO) comprise twelve ontologies that are designed to represent and integrate taxonomies of
generic classes and relations across all domains of interest.

CCO is a mid-level extension of Basic Formal Ontology (BFO), an upper-level ontology framework widely used to structure
and integrate ontologies in the biomedical domain (Arp, et al., 2015). BFO aims to represent the most generic categories
of entity and the most generic types of relations that hold between them, by defining a small number of classes and
relations. CCO then extends from BFO in the sense that every class in CCO is asserted to be a subclass of some class in
BFO, and that CCO adopts the generic relations defined in BFO (e.g., has_part) (Smith and Grenon, 2004). Accordingly,
CCO classes and relations are heavily constrained by the BFO framework, from which it inherits much of its basic
semantic relationships.

The CCO provide semantics for concepts and relations that are used in most domains of interest. The utility of the CCO
comes from preventing BFO-compliant domain-specific ontologies from needlessly duplicating common concepts or from
forcing such ontologies to include concepts outside of their domain (e.g. organization in the Ontology of Biomedical
Investigations).

This utility has been realized by a number of U.S. Government sponsored projects in which either existing BFO compliant
ontologies were aligned to the CCO or domain ontologies were created by using the CCO as a starting point and adding
classes and properties as needed.

The names of a sample of these domain ontologies are provided in the list below.

The U.S. Government holds Government Purpose Rights on all of these domain ontologies. To obtain one or more of these
domain ontologies for a government purpose it will be necessary for a government representative to contact the
government sponsor of the development of the ontology. CUBRC can facilitate these connections so if interested please
use the contact link at the bottom of https://www.cubrc.org/index.php/data-science-and-information-fusion/ontology .

