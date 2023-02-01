# UPF_Placement_and_Chaining
This repository releases the source-code of the solutions for UPF placement and chaining problem, proposed in the article "Efficient solutions to the placement and chaining problem of User Plane Functions in 5G networks"[1] and published as open access in  the Journal of Network and Computer Applications. These solutions addresses the 5G UPF placement problem considering the possibility of split UPF functionalities into smaller microservices (Virtual Network Function, VNFs) and chain them together as required by service requests (PDU sessions). To this aim, PDU sessions are modeled as SFC requests (SFCRs). Their main goal is optimizing provisioning costs and quality of service.

The solutions take into account several aspects of the system such as UPF-specific considerations, SFC topology (single and multiple branches), VNF order constraints, service demands, and physical network capacities. Specifically, an integer linear programming (ILP) model, a heuristic algorithm (Priority and Cautious-UPF Placement and Chaining, PC-UPC) and a simulated annealing (SA) metaheuristic are proposed.

Article link: https://www.sciencedirect.com/science/article/pii/S1084804521002654

This repository contains three folders (one for each solution):
		- ILP: Code of the exact olution.
		- DP-UPC: Heuristic algorithm
		- SA-UPC: SA-based metaheuristic
		

# References:
[1] Leyva-Pupo I, Cervelló-Pastor C. Efficient solutions to the placement and chaining problem of User Plane Functions in 5G networks. Journal of Network and Computer Applications. 2022 Jan 1;197:103269.
