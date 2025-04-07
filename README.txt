This package contains the instances described in the paper:

Comparison of Compact Formulations for the Electric Vehicle Routing Problem. 

We give a brief description of the package content. 

The instances are obtained as described in Section 5.1.

--  Benchmark Instances:
     
    ** Datas
  
	The number of customers, rehcarging stations are given in the second row "A2 : B2";
	
	The size of fleet, load capacity, and battery capacity are showed in the fifth row "A5 : C5“;
	
	From the ninth row：
	
	Column "NO." shows the number of each vertex, where ”D“, ”C“, ”F“ denote depot, customers,
	and recharging stations, respectively;
	
	Column ”XCOOR“ and "YCOOR" give the x- and y-axis coordinates;
	
	Column "Demand" proivde the demand of vertices, where the demand of depot and recharging stations equals to 0. 

    ** Distance
    
    Let x_ij = x_i - x_j and y_ij = y_i - y_j. The distance d_ij between vertex i and vertex j is calculated by 
	Euclidean distance. Specifically,  d_ij =sqrt( pow (x_ij, 2) + pow (y_ij, 2))/100.
	
--  Computational Results:

	Column "Set" provides six sets of benchmark instances;
	
	Column "Inst." lists the name of each instance.
	
	The following columns presents:
	
	#Opt -- The number of instances solved to optimiality;
	
	LP -- the linear relaxation bound;
	
	UB -- the upper bound;
	
	LB -- the lower bound;
	
	Delta_1 -- the percentage gap between the value of best-known solution and the LP bound;
	
	Delta_2 -- the percentage gap between the upper bound and lower bound;
	
	t(s) -- the computation time in seconds;
	
	BUB -- the value of best-known solution over all formulations.
	
	The last row of each set provides the sum of #Opt and the average values of LP, UB,LB,Delta_1,Delta_2,t(s)，and BUB.
	