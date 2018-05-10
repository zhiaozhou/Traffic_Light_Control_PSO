# Swarm intelligence for traffic light scheduling: Application to Downtown Area in Los Angeles

Description
=====
Nowadays, most cities around the world are suffering from congestion, security, parking, pollution and many other problems derived from an excessive vehicular traffic. Finding an better principle for scheduling traffic lights is commonly considered to be a helpful way to reduce those problems by improving the flow of vehicles through the cities when most city planning departments are not willing to make significant improvement on urban area infrastructure due to many reasons. However, especially in urban area of large cities like New York and Los Angeles, thousands of new traffic light has emerged with the urban��s development, making traffic lights schedule more complicated dramatically because of a great number of new combinations. In this situation, applying an optimal algorithm for scheduling traffic lights is a necessary choice.

Among several evolutionary methods, optimization strategy based on particle swarm optimization(PSO) has proved its usefulness to the optimization of cycle programs of traffic lights. One related research proposed a swarm intelligence approach to find successful cycle programs of traffic lights[1] . Using a microscopic traffic simulator, the solutions obtained by PSO are evaluated in the context of two large and heterogeneous metropolitan areas located in the cities of Malaga and Sevilla in Spain which typically represents regular and irregular road structure respectively. The simulation result shows that, for both regular and irregular road structure, significant profits are obtains in terms of two main indicators: the number of vehicles that reach their destinations on time and the global trip time. However, a semi-regular road structure area(combination of both regular and irregular road) has not been considered, like Los Angeles which represents most large cities. The purpose of this paper is to test the robustness of PSO in terms of providing the optimal traffic lights cycle programs by implementing the optimization and simulation processes elaborated in the paper on a central area of downtown in Los Angeles. After running the algorithm for 10 iterations (1000 global steps), our objective function -- the number of cars completing their trips has increased by 22.3% to 252 from 206 at step 0. However, we found that PSO is too slow to conduct in real-world problems and the states of the vehicles could be more complex and more dynamic than we set in this paper. Consequently, more algorithms should be tried and compared with PSO in future works.  

Paper
=====
You can find the pdf file of our final paper [here](./Paper/FinalReport.pdf)