This code allows for calculating the Factorial of a number through a distributed system
factorialAPI.war: contains the main component of the system, the .war must be placed in an application 
	server(tomcat, wildfly, etc.)
 	Note : make sure to change the IP addresses and ports for the subsystems to suit your case, these are available
		at the class FactorialService.java inside the initiateSystem(...) method
	       	 
Sous-Système.jar : contains the code for a subsytem, a class with a main method is to be duplicated on 4 machines
	Note : make sure to set the ports accordigly to what is defined in the main component (factorialAPI)
	 