MIRO – Minimum Information for Reporting of an Ontology
==============

## Published 05 November 2020

**Editors**:

Jérôme Dauba, Telecom Paris MS IA

Antoine Boulat, Telecom Paris MS IA

Jean-Charles Lévy, Telecom Paris MS IA


# Summary 
This document contains the Minimum Information for Reporting of an Ontology (MIRO) guidelines. 

# Guidelines

## A. Basics

### A.1 Ontology name

|  | Specification |
|---|---|
| **Description:** | Car selection based on CO2 footprint and price |

----

### A.2 Ontology owner

|  | Specification |
|---|---|
| **Description:** | Jerome Dauba jerome.dauba@telecom-paris.fr , Jean-Charles Lévy jean-charles.levy@telecom-paris.fr , Antoine Boulat antoine.boulat@telecom-paris.fr  |

----

### A.3 Ontology license

|  | Specification |
|---|---|
| **Description:** | Apache 2.0 |

----

### A.4 Ontology URL

|  | Specification |
|---|---|
| **Description:** | http://www.semanticweb.org/jerom/ontologies/2020/9/car/v2 |

----

### A.5 Ontology repository

|  | Specification |
|---|---|
| **Description:** | https://github.com/AntoineBoulat/miro-master |

----

### A.6 Methodological framework

|  | Specification |
|---|---|
| **Description:** | Analyse the lifecycle of car (electric and thermic) and then use some features of eco-conception. We weight the classification by the energy mix of each country. But ecologic choice has economic impact. So we have weight the economic impact by the purchase power of the user. |

----

## B. Motivation

### B.1 Need

|  | Specification |
|---|---|
| **Description:** | It cans help, for people living in different country, classify wich kind of car to choose to minimize our ecological impact. We weight this result by the purchase power of user. https://youmatter.world/en/are-electric-cars-eco-friendly-and-zero-emission-vehicles-26440/ |


----

### B.2 Competition

|  | Specification |
|---|---|
| **Description:** | Our ontology is not based on another one. We follow the pizza ontology to make the best model as possible. |

----

### B.3 Target audience

|  | Specification |
|---|---|
| **Description:** | This ontology is realised in the course IA301 at Telecom Paris. The audience will be our classmate and the teacher. |


----

## C. Scope, requirements, development community

### C.1 Scope and coverage

|  | Specification |
|---|---|
| **Description:** | The domain of field is PLM (Product Lifecycle Management). The question would be : what is the best car to buy if I'm living in a specific country weight by my purchase power ? https://www.transportenvironment.org/sites/te/files/downloads/T%26E%E2%80%99s%20EV%20life%20cycle%20analysis%20LCA.pdf |

----

### C.2 Development community

|  | Specification |
|---|---|
| **Description:** | Group of student at Telecom Paris in MS IA supervize by Natalia Diaz |

----

### C.3 Communication

|  | Specification |
|---|---|
| **Description:** | Online meeting |

----

## D. Knowledge acquisition

### D.1 Knowledge acquisition methodology

|  | Specification |
|---|---|
| **Description:** | We spend a long time compare the data for the different model of vehicule. The data are sometimes incoherent from one site to another. We choose to keep data from non-governmental organization and also from ADEME (french national ecological agency), especially for the energetic mix of each country. We regroup all the data founded in the xls join in this project. |

----

### D.2 Source knowledge location

|  | Specification |
|---|---|
| **Description:** | -	https://www.bilans-ges.ademe.fr/documentation/UPLOAD_DOC_FR/index.htm?moyenne_par_pays.htm
-	https://greenercars.org/greenercars-ratings/how-we-determine-ratings
-	https://www.greenpeace.org/international/story/24136/these-12-car-companies-are-setting-the-world-on-fire/ |

----

## E. Ontology content

### E.1 Knowledge Representation language

|  | Specification |
|---|---|
| **Description:** | OWL |

----

### E.2 Development environment

|  | Specification |
|---|---|
| **Description:** | Protégé |

----

### E.3 Ontology metrics

|  | Specification |
|---|---|
| **Description:** | 34 class, 8 object properties, 3 data properties, 238 axioms, 16 individuals in the ontology. |


----

## F. Managing Change

### F.1 Sustainability plan 

|  | Specification |
|---|---|
| **Description:** | Feel free to enhance the model. This is a student project but the aim is interesting and ecologic. |
----

### F.2 Entity deprecation strategy 

|  | Specification |
|---|---|
| **Description:** | The owl:DeprecatedClass; no class is deleted from the ontology, but deprecated classes are labelled as obsolete with an annotation property. |

----

## G. Quality Assurance

### G.1 Testing

|  | Specification |
|---|---|
| **Description:** | All classes in the ontology are satisfiable. Using HermiT, the ontology is able to classify car (instance) in different class (eco_friendly, very_polluting for exemple). You just need to start the reasoner to perform this. We also use DL Query to dermine which car to chosse in which situation. ex DL Query : USA and medium_price_car and average_polluting_car => Renault_zoe_USA. |

----

### G.3 Example of use

|  | Specification |
|---|---|
| **Description:** | DL Query : USA and medium_price_car and average_polluting_car => Renault_zoe_USA
to perform new classification, feel free to add more individual.|


----


### G.5 Evidence of use

|  | Specification |
|---|---|
| **Description:** | The Car Ontogy is used to classify cars based on CO2 footprint and price. We consider both ecological and economic parameter. |

----

