#How to Create the Widoco Documentation 

 The Commands for the Documentation Creation of Widoco is 
 java -jar widoco.jar -ontFile clean.owl -outFolder ./doc -uniteSections
 you just open the cmd and go the folder where your ontology and jar file is present and then run this comman 
 it will create and index.html in a doc folder you can open the doc folder and and then open Html file to see 
 the widoco documentation
  
#Reporoduceability and Availability Section 

Here I will describe the section so that if someone want to practice and run and check the reasoning system even he is non tecnical guy so it will be easiar for him to understand the process.
1.	 Open protege and create Ontology and make the relationship between the object properties and data properties 
2.	Add the labels and comments on each section of the class and on each object properties and data properties.
3.	After adding the labels and comments you can add the individuals and also connect them with the help of the object properties and data properties to the classes that are described in our ontology.
4.	Now you can run the from the menu bar click on reasoner and then click on your required reasoner I used the hermit but there is also pallet reasoner is available
5.	If you defined your classes properly their relationship properly than the individuals that are related and that are defined according to the legal logical conditions will infer properly in this section instances on the right side of the ontology if you click on a clause for example if you click on a claass called Compliant Agent then individual named agent with license will appear properly and infer end this action.
6.	Now our ontology is working properly and inffering the required results Now you can save the ontology and in the form of RDF OWL syntax
7.	The next step is to create the diagram with the help of YED editor in which you can create the diagram that is showing the relationships between the classes and object properties and data properties and their interconnected relationships that how they are connected with each other .The Diagram is available on the link that contains the ontology and other things I will also add the link here below
8.	https://github.com/SyedBilal61/legal-ontology-credit-licensing 
9.	There is a tool called Widoco (lode) , This tool is used for generating documentation of the ontology, So the researchers practitioners and the non technical users can read the documentation and how they are presented and how they are used the logical conditions in the ontology easily.
10.	To use this there are multiple ways but there is a condition that the ontology file and the widoco Jar file both should be in the same folder and you can run these commands by the bash through CMD and then going to folder where these files are present.
11.	The Commands for the Documentation Creation of Widoco is java -jar widoco.jar -ontFile clean.owl -outFolder ./doc -uniteSections you just open the cmd and go the folder where your ontology and jar file is present and then run this comman it will create and index.html in a doc folder you can open the doc folder and and then open Html file to see the widoco documentation.
12.	After this you need To run SPARQL queries These queries present in the github repository and you can run this and check the outcomes.
13.	To run these you should the software called Graph DB Editor and you should create repository in that folder and later after creating the repository you should import the owl that is your original ontology file and then go quries section and run the queries.The example for a simple query is as follows (Get all agents
SELECT ?agent
WHERE {
  ?agent a <http://www.example.org/credit-licensing-ontology#Agent> .
})
14.	From there is a notepad field called queries Text And you can check all the queries that they are properly and give the desired and expected outcomes.
15.	Now here comes the one of the most crucial and important part that is the UI interface of our ontology as described earlier although the UI is something else that That over ontology is going to but it is developed for better understanding and for the understanding of researchers and non technical users.
16.	To do this you use Github and clone the following repository
https://github.com/SyedBilal61/Credit-ontology-UI 
17.	After cloning the repository you can open any of HTML file are I created the GitHub pages directly so you don’t need to clone the GitHub and you can check the web page directly on the web page without refreshing the page so there is a folder on the right side of the GitHub a file name called Github Pages and you select it and it will open a you UI for our ontology.
18.	There are three sections in the navigation bar 1 that checking for the compliance checking the second is the input form in which we can input our data and check the compliance results and Information is about the researcher and the mentor who created these ontologies.
19.	Both of the Github repositories links are all the following so you may check and check the required results and check that they are infringing properly if you want to understand it better.
i.	https://github.com/SyedBilal61/Credit-ontology-UI 
ii.	https://github.com/SyedBilal61/legal-ontology-credit-licensing

 
