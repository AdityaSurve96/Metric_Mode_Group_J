# Metric_Mode

_This Project is aimed at analyzing various open source systems from “The Apache Software Foundation”. The systems first undergo a data collection process under which they are subjected to various tools which collect data for different metrics. Later this collected data undergoes Correlation analysis inorder to find some rationales based on the data. By Performing this assessment, we get an idea of the overall quality of the SUT (System under test) as well as helps us to get an idea of the impacts of decision made during the software development life cycle._ 

### Metrics
The chosen systems undergo a rigorous analysis under different tools to measure various metrics including:  

1. Metric 1- Code Coverage Metric------( Statement Coverage )
2. Metric 2- Code Coverage Metric------( Branch Coverage )
3. Metric 3-Mutation Score
4. Metric 4-Cyclomatic Complexity-----( McCabe )
5. Metric 5-Code Churn-----------------( A sofware Maintainance Metric)
6. Metric 6-Code Smells-----------------( A software quality metric )

### Projects
We have Chosen the following Projects for analysis:-  
1. Commons Math    		     SLOC ~ 186K  
   * Versions:-
      * 3.6
      * 3.4
      * 3.3
      * 3.1
      * 2.1
2. Commons Collection		   SLOC ~ 130K  
    * Versions:-  
      * 3.6
      * 3.4
      * 3.3
      * 3.1
      * 2.1
3. Commons Lang			        SLOC ~ 80K 
    * Versions:-  
      * 3.9
      * 3.8.1
      * 3.7
      * 3.6
      * 2.5
4. Commons Digestor	        SLOC ~ 27K 
    * Versions:-  
      * 3.2
      * 3.1
      * 3.0
      * 2.1
      * 1.8.1
4. Commons Configuration 	SLOC ~ 600K
    * Versions:-  
      * 2.4
      * 2
      * 2.2
      * 2.1
      * 2.0

### Tools/Plugins used for Metric Measurement

1. Jacoco Maven Plugin:-  
   * This Plugin has been used to collect data for Metric 1,2 and 4.
   * Each __pom.xml__ file of each version of each Project contains this plugin in __Build.Plugins.Plugin Tag__.
   * Inorder to generate the reports we follow below steps:-  
      1. Insert the plugin in pom.xml in the root directory of the project
      2. Run Maven Clean Goal.
      3. Run the Maven Test Goal.
   * We get the reports in jacoco-ut folder which is currently present in the above folder structure in each project/version sub-folders


