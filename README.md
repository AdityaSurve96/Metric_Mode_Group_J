# Metric_Mode



This Project is aimed at analyzing various open source systems from “The Apache Software Foundation”. By Performing this assessment, we get an idea of the overall quality of the SUT (System under test) as well as helps us to get an idea of the impacts of decision made during the software development life cycle. The chosen systems undergo a rigorous analysis under different tools to measure various metrics including

	* Code Coverage
	* Cyclomatic Complexity
	* Mutation Score 
	* Code Churn – A software Maintenance Attribute
	* Code Smells- A Software Quality Attribute


We have Chosen the following Projects:-
	1  Commons Math    			SLOC ~ 186K 
			* Versions :
			  	3.6 			
			  	3.4				
			  	3.3				
			  	3.1				
			  	2.2					
	2  Commons Collection		SLOC ~ 130K
			* Versions :
			  	3.6 				
			  	3.4					
			  	3.3					
			  	3.1					
			  	2.2					 
	3  Commons Lang				SLOC ~ 80K
				* Versions :
			  	3.6 				
			  	3.4				
			  	3.3				
			  	3.1				
			  	2.2					
	4  Commons Digestor			SLOC ~ 27K
				* Versions :
			  	3.3.2
			  	3.3.1
			  	3.3.0
			  	2.1
			  	1.8.1 
	5  Commons Configuration 	SLOC ~ 600K
				* Versions :
			  	3.6 			
			  	3.4				
			  	3.3				
			  	3.1				
			  	2.2				 




The structure of the Repository is as follows:
	* It contains a Main Project Folder which has 5 Subfolders for each of the 5 different Proejects
	
	* Each Individual subfolder for each project contains the following :- 
			*  5 subfolders for 5 versions of that particular project with folder name as Version name
				1). In each Version there is a pom.xml file with the Configurations for
				    for Jacoco Plugin , Pitest Plugin( For some files), and Sonar Lint Plugin (For some Files).


				2). Next there is a Jacoco-ut folder with the Jacoco Reports in 3 formats (CSV,XML,HTML).

				3). Next there is a Pitest Report in pit-reports folder in the latest version of each project.

				4). For Some Projects versions there is a snapshot of Sonar Analysis results which shows the Code smell Value.



