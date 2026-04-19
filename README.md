
Irish Dance Ontology
Description
This project presents an ontology of the Irish dance domain, designed to model the relationships between dancers, teachers, schools, and competitions.  The aim is to capture structured knowledge about Irish dance in a way that can support reuse, querying, and future expansion.
The ontology was developed using Protégé and demonstrates key ontology engineering concepts, including class hierarchies, object properties, data properties, individuals, and reasoning.
Purpose
The purpose of this ontology is to represent the core structure of Irish dancing as a domain.  It focuses on
-	The roles of people involved (e.g., dancers, teachers, adjudicators, and musicians).
-	The organisation of dance schools
-	Participation in competitions and events
-	The classification of dance types
This ontology could be extended in the future to support cultural heritage preservation or digital archives of Irish dance.
Ontology Structure
Classes
The main classes in the the ontology include:
-	Person
o	Dancer
o	Teacher
o	Adjudicator
o	Musician
-	School
-	Event
o	Competition
-	DanceType
o	Reel
o	Slip jig
o	Single jig
o	Light jig
o	Heavy jig
o	Hornpipe
-	SetDanceType
o	JigTimeSetDance
o	HornpipeTimeSetDance
Object Properties
-	hasRole – links a person to that role
-	belongsToSchool – connects a dancer to a school
-	hasDance – inverse of belongsToSchool
-	participatesIn – links dancers to competitions/events
These relationships allow us to model how individuals interact within the Irish dance ecosystem.
Data Properties
-	hasName
-	has Age
-	hasCompetitionsName
-	hasYear
-	hasLocation
These properties store descriptive information about individuals and events.
Individuals (Examples)
-	Dancer_001 – Mary Browne (Age 10)
-	Dancer_002 – John Doe (Age 12)
-	Teacher_001 – Regina Lawlor
-	Teacher_002 – Olivia Lawlor
-	Competition_001 – World Irish dance Championships (2026, Glasgow)
-	School – Premier Dance Academy
Reasoning and Inference
A reasoner was used within Protégé to validate the ontology and infer relationships.
For example
-	Ensuring dancers are correctly linked to schools
-	Checking class consistency
-	Verifying property constraints
Queries
SPARQL queries were implemented to retrieve information from the ontology
Example queries include:
-	Retrieve all dancers and then schools
-	List competitions and participating dancers
-	Identify teachers associated with schools
Linked Data
The ontology is designed with reuse in mind and could be extended to link with external cultural or heritage datasets in the future
Tools Used
-	Protégé (Ontology Development)
-	OWL (Web Ontology Language)
-	SPARQL (Querying)
-	GitHub (version control and sharing)
Future Work
This ontology could be extended to include
-	Costumes and music
-	Dance scoring and judging criteria
-	Historical evolution of Irish dance
-	Integration with digital archives such as the Digital Repository of Ireland
Conclusion
This project demonstrates how an ontology can be used to model a real-world cultural domain.  While simplified, it provides a foundation for further development and highlights the potential of semantic technologies in preserving and structuring knowledge about Irish dance.
Author
Patrice Lawlor 
MSc Computing (Human Centred Systems)
