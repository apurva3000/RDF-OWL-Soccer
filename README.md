RDF-OWL-Soccer
==============

A project showing the use of OWL/RDF for soccer records

Note: This project was done just for demonstration purposes in academic use only.

The Application contains the soccer.owl which is a rdf/owl file containing our ontology. 
It also contains the interactive session which will list down all the commands used and queries done.
Plus a screenshot showing the Protege editor (which we have used) and the project.



Brief description of the application and its domain:
------------------------------------------------------
This is a mini application developed for some soccer records. It contains information such as National Teams, League clubs, the championships, managers and soccer players. However please note that it does not contain a large dataset, as I made the application to understand the functionalities of the different techniques with limited set of data. It contains data for English Premier League 201213 season with only top 4 teams, their managers and just some players. It also contains data for Euro 2012 of final 2 teams in the tournament, their managers and
some players. Note: This is why when we define the soccer players, we mention their clubs/national teams if they are in our current set that we have taken.
The application is created using Protege editor and queried using built in DL query processor
(Reasoner:FaCT++). It uses dbpediaowl ontology as the third party vocabulary which provides several classes, object properties and data properties for building sports KB. It also uses ‘foaf’ vocabulary for describing persons.

Brief use case description:
-----------------------------
Our KB aims answering several kinds of questions(Note: The data set is restricted/limited and covers to the limit specified above):
Which manager represents which national team/ clubs? (Using variety of queries)
Who are players of the particular clubs and national teams?
Which player played in which tournament? Which teams which were in which tournament?
The goalkeepers in the various tournaments?
Which players played both in Euro 2012 (as a part of national team) and EPL (as a part of club)?

Conclusion:
---------------
The learning outcomes of this assignment is the basics of how to author and query very simple semantic models using the W3C Semantic Web technologies. Make a rdf/owl KB and then query it using query processors.
The KB can be used for getting the required information for some soccer records while building some information portal. But since the domain area is very wide and there are plenty of relationships possible and huge amount of data that can be put in this case, our KB is used only to understand the working of the technologies.
