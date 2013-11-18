"Effects of Extrinsic Mortality on the Evolution of Aging: A Stochastic Modeling Approach"

There are six java 1.6 files included:

Creature.java 			: contains methods and variables required for modeling individuals.
Optimization.java		: Holds parameter ranges for simulated annealing optimization
Parameters.java			: Wrapper class for the set of parameters being optimized along with routines for 				generating random parameters.
SimulatedAnnealingAging.java	: Main class used for running the simulated annealing optimization
Simulation.java			: Main class for running simulations (called repeatedly during 								optimization) 	
Ticker.java			: Thread class that actually performs an individual simulation.

Please compile the java classes using javac, and run the SimulatedAnnealingAging.class or Simulation.class using the java command. Simulation parameters can be adjusted manually by changing the variables in Simulation.java and recompiling.

Questions and comments can be sent to maxshok@gmail.com.

