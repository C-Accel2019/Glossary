# C-Accel 2019 Glossary

---

_This living document serves as a community and consensus-driven glossary of terms for C-Accel 2019 teams in track A and B with the hope to accelerate convergence on common goals and measures for success. In cases where agreement has not yet been reached or where a plurality of views is beneficial, multiple versions can be maintained and term in a single version may be defined multiple times by indicating which teams utilize them. This will enable teams to interoperate without enforcing a single artificial view._

---

### Index ###
1. [AI (Artificial Intelligence)](#AI-Artificial-Intelligence)
1. [Embedding](#Embedding)
1. [GeoAI (Geographic Artificial Intelligence)](#GeoAI-Geographic-Artificial-Intelligence)
1. [Geospatial Interoperability](#Geospatial-Interoperability)
1. [Knowledge](#Knowledge)
1. [Knowledge Graph (KG)](#Knowledge-Graph-KG)
1. [Knowledge Graph Schema](#Knowledge-Graph-Schema)
1. [Link Prediction](#Link-Prediction)
1. [Linked Data](#Linked-Data)
1. [Ontology](#Ontology)
1. [Open Knowledge Network (OKN)](#Open-Knowledge-Network-OKN)
1. [OWL (Web Ontology Language)](#OWL-Web-Ontology-Language)
1. [Question Answering](#Question-Answering)
1. [RDF (Resource Description Framework)](#RDF-Resource-Description-Framework)
1. [Reasoning](#Reasoning)
1. [Representation Learning](#Representation-Learning)
1. [Semantic Interoperability](#Semantic-Interoperability)
1. [Semantic Web](#Semantic-Web)


## AI (Artificial Intelligence)

In contrast to natural intelligence, which is the nature of human beings, artificial intelligence is the study of allowing machines to have a similar level of intelligence as humans, such as 'learning' and 'problem solving'. In modern computer science, a main stream of AI is to mimic the neural structure of human brains into designing the architecture of computational models, which are further trained using a large number of data. This type of approaches is commonly named as machine learning.  Techniques developed from artificial intelligence have been used in applications such as image classification and segmentation, language translation, and self-driving cars.

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Embedding

Originally, in mathematics, an embedding is one instance of some mathematical structure contained within another instance. In [machine learning], embeddings refer to real value vectors as output or intermediate products of neural networks which are treated as representations of symbolic, categoric instances in a hidden space. An embedding can represent a word, a word phrase, a sentence, a paragraph, an image, a sound, an entity/relation in a knowledge graph, and so on.

\[**Used by:** A-6677\]

[Back to Index](#Index)


## GeoAI (Geographic Artificial Intelligence)

GeoAI is the marriage of geography and artificial intelligence. On one hand, GeoAI leverages the state-of-the-arts in [AI (Artificial Intelligence)](#AI-Artificial-Intelligence) to address geospatial challenges, such as weather prediction, land use and land cover mapping, and traffic forecasting. On the other hand, GeoAI contributes to the [AI (Artificial Intelligence)](#AI-Artificial-Intelligence) community by introducing spatiotemporal knowledge into the design of methods. One example is the spatially-explicit reinforcement learning to summarize places in a knowledge graph.  

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Geospatial Interoperability

Interoperability measures the ability of different computer systems to communicate and access, exchange, integrate, and (re)use data and other resources autonomously without human intervention. Geospatial Interoperability deals with the interoperability among geospatial systems and software in particular. Standardization is a typical means to achieve interoperability. For instance, International Standardization Organization (ISO) has defined a series of metadata standards (ISO 19115, ISO 19139) to standardize the organization of metadata. Open Geospatial Consortium (OGC) has developed a wide range of web service specifications to define standardized interface for the representation, retrieval and parsing of geospatial data of various types.

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Knowledge

A term typically referring to the second concept from the top of a DIKW (Data, Information, Knowledge, Wisdom ) model pyramid. The term is used to indicate internalized, synthesized, organized, or familiar information that can readily be applied, e.g., in domain transfer tasks, and to put new information into perspective. In the context of symbolic representations, the term is often used to contrast methods that aim at making semantics machine-understandable from those that merely operate on a syntactic level.  In the context of [knowledge graphs](#knowledge-graph-kg) and in contrast to epistemology, the term is loosely used to describe statements (about the world) irrespective of whether these statements are factual. 

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Knowledge Graph (KG)

A combination of technologies, specifications, and data cultures for densely interconnecting (Web-scale) data across domains in a human and machine readable and reasonable way. The term knowledge graph itself does not prescribe any particular technology stack. More formally, a knowledge graph (as a set of statements) can be considered as a node and edge labeled directed multigraph. The largest publicly available knowledge graph is the so-called [Linked Data](#Linked-Data) cloud based on the [RDF](#RDF-Resource-Description-Framework)/[Semantic Web](#Semantic-Web) technology stack.

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Knowledge Graph Schema

A Knowledge Graph Schema informs the structure of a knowledge graph. It can be expressed, e.g., by means of an [ontology](#Ontology) using  [OWL](#OWL-Web-Ontology-Language), or the SHACL Shapes Constraint Language, both of which are W3C standards. Knowledge Graph Schemas can often be understood to be knowledge graphs of classes (types) and their relationships. 

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Link Prediction

A key part for knowledge graph completeness, since no knowledge graph is ever complete. In this project, link prediction is to predict whether there are missing labeled edges in knowledge graphs. It typically includes entity prediction, which is to predict the subject given the relation and the object, or to predict the object given the subject and the relation, and relation prediction, which aims to predict possible relations between two entities. Knowledge graph embedding techniques are widely studied to approach this. 

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Linked Data

Linked data currently constitutes the largest publicly available [knowledge graph](#Knowledge-Graph-KG), expressed using W3C standards [RDF](#RDF-Resource-Description-Framework) and [OWL](#OWL-Web-Ontology-Language). The Semantic Web field has been creating linked data since about 2007. https://lod-cloud.net/ lists over 1,200 interconnected knowledge graphs which are publicly accessible. A count from 2015 identified over 37 billion [RDF](#RDF-Resource-Description-Framework) triples, i.e., node-edge-node [knowledge graph](#Knowledge-Graph-KG) statements which could be retrieved from the World Wide Web.

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Ontology

A shared domain model usually expressed using the W3C standard Web Ontology Language ([OWL](#OWL-Web-Ontology-Language)). OWL can be serialized in [RDF](#RDF-Resource-Description-Framework), i.e., an OWL document can be understood to be a [knowledge graph](#Knowledge-Graph-KG) of classes (types) and their relationships. Ontologies can constitute [knowledge graph schemas](#Knowledge-Graph-Schema). 

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Open Knowledge Network (OKN)

It may make sense to distinguish between *open-knowledge* networks and open *knowledge-networks*. The first case implies a social structure that provides the means to make [knowledge](#Knowledge) openly available. The second case, in contrast, describes the structure of the data and the mode of contributions to such structure. To avoid conflicts with the narrower and more technical notion of a [knowledge graph](#knowledge-graph-kg), we define an open knowledge network in the first sense. An OKN is a network consisting of partners across academia, industry, and the government set out to foster the publication, retrieval, and integration of openly available knowledge. Such a network may also foster a culture of opening up otherwise silo-ed knowledge. 

\[**Used by:** A-6677\]

[Back to Index](#Index)


## OWL (Web Ontology Language)

A shared domain model usually expressed using the W3C standard Web Ontology Language (OWL). OWL can be serialized in [RDF](#RDF-Resource-Description-Framework), i.e., an OWL document can be understood to be a [knowledge graph](#Knowledge-Graph-KG) of classes (types) and their relationships. Ontologies can constitute [knowledge graph schemas](#Knowledge-Graph-Schema). OWL is based on a so-called description logic, which essentially is a decidable sublanguage of first-order predicate logic. As such, OWL allows for logical (deductive) [reasoning](#Reasoning), and an OWL document together with an (RDF) knowledge graph constitute a knowledge base in the sense used in the subfield of Artificial Intelligence known as "Knowledge Representation and Reasoning". For standards documents, see  https://www.w3.org/TR/2012/REC-owl2-primer-20121211/

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Question Answering

In the field of [natural language processing], Question Answering (QA) refers to the methods, processes, and systems which allow users to ask questions in the form of natural language sentences and receive one or more answers, often in the form of
sentences. Almost all QA systems answer a given question based on their internal [knowledge bases] (KB). According to the nature of such knowledge bases, current QA research can be classified into three categories: unstructured data-based QA (e.g. QA systems based on unstructured text), semi-structure table-based QA (e.g. QA systems based on tables from Wikipedia pages without any schema information), and structured-KB-based QA (so-called [semantic parsing]). In the field of Semantic Web, question answering over knowledge graphs is considered as one type of structured-KB-based QA which aims at translating a natural language question into a machine understandable program such as SPARQL and Lambda calculus.

\[**Used by:** A-6677\]

[Back to Index](#Index)


## RDF (Resource Description Framework)

A W3C standard (2004; revised 2012) for expressing [linked data](#Linked-Data) and [knowledge graphs](#Knowledge-Graph-KG). A corresponding [knowledge graph schema](#Knowledge-Graph-Schema) can be expressed as an [ontology](#Ontology) in [OWL](#OWL-Web-Ontology-Language). A [knowledge graph](#Knowledge-Graph-KG) is expressed in [RDF](#RDF-Resource-Description-Framework) as a set of so-called RDF triples, i.e., of node-edge-node relations in the [knowledge graph](#Knowledge-Graph-KG). Nodes and edges are identified using IRIs. As part of the RDF standard, RDF Schema provides vocabulary for node and edge types (called classes) and simple relationships between them. For more complex relationships, the Web Ontology Language [OWL](#OWL-Web-Ontology-Language) can be used. For standards documents, see https://www.w3.org/TR/rdf11-primer/

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Reasoning

Computational reasoning can in many forms, and the term is often used ambiguously. The W3C [Semantic Web](#Semantic-Web) standards [RDF](#RDF-Resource-Description-Framework) and [OWL](#OWL-Web-Ontology-Language) natively support so called *deductive* reasoning, which is based on formal logic and logical consequences which can be derived from given facts, rules, and/or other statements made in formal logic. E.g., given the statement that *Black Beauty* is a horse, and the statement that every horse is a mammal, we can arrive at the logical consequence that *Black Beauty* is a mammal. The example just given can be expressed in [RDF](#RDF-Resource-Description-Framework), and the [RDF](#RDF-Resource-Description-Framework) standard prescribes this kind of reasoning. The Web Ontology Language [OWL](#OWL-Web-Ontology-Language) can be used to express more complex relationships that can then also be used for deductive reasoning.

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Representation Learning
The aim of representation learning is to learn representations of data that make it easy for machine learning models to extract information for different downstream tasks. In contrast to features harvested by labor-intensive feature engineering, these representations here are automatically learned by different well-designed machine learning/deep learning methods. Good representations of data are expected to convey human priors about the world, e.g., some representations can be shared across tasks, to be distributed, which means a learned representation should be able to capture most of the information hidden in the data, to be disentangled underlying explanatory factors and to be deep and abstract. 

\[**Used by:** A-6677\]

[Back to Index](#Index)


## Semantic Interoperability

Semantic interoperability focuses on the semantic understanding of data and software for better and smarter data integration and synthesis. Common interoperable solutions define the syntax for structuring a dataset or invoking an operation, i.e. what are the input, output and number of parameters. Semantic interoperability moves interoperability up to the next level at which different computer systems do not only agree on the protocol to exchange data, but also have a shared understanding on the meanings of data. Semantic interoperability is achieved by machine reasoning on top of a controlled, shared vocabulary, or an ontology that is used to annotate data and is often encoded in machine-understandable formats, such as RDF or OWL.


\[**Used by:** A-6677\]

[Back to Index](#Index)


## Semantic Web

A field of research concerned with developing methods and tools for efficient data sharing, discovery, integration, and reuse. The community is strongly aligned with W3C standards such as RDF, OWL and SPARQL for expressing and manipulating knowledge graphs. The Semantic Web field also gave rise to Linked Data which constitutes the currently largest publicly available knowledge graph. 

\[**Used by:** A-6677\]

[Back to Index](#Index)

