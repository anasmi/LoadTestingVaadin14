# Load testing of Vaadin Flow applications

Preliminary, this is a repository that contains a JMeter script file created within my Master's thesis. It was excluded from the thesis due to its big size. Later on, all the other static files should be added here as well.

Master thesis can be found in full text here : https://www.utupub.fi/handle/10024/149315

## Running a gatling script
1.	Install Gatling on your computer
2.	Put a simulation file (ends with .scala) under user-files/simulations
3.	Put resources such a txt files, containing requests payloads and .csv files (feeders used in simulation) under user-files/resources directory
4.	Navigate to bin directory and execute gatling.bat 
5.	In console you will see a list of available simulations and a number assigned to each- select wanted one
6.	Then you are prompted for some description: you can simply press enter
7.	After simulation has run, results are available under results directory inside a simulationname-timestamp folder. index.html file contains an overview with min and max running times 

*All directories are located under gatling installation folder

