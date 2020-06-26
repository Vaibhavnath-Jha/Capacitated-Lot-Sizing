# CLSP
Implementation of Capacitated Lot Sizing Problem as a Mixed Integer Linear Programming Problem using CPLEX's python library DOCPLEX

##### *Special Case:* 
<br/>This is one of the combination where Lagrangian Relaxed model gives lower bound and not the solution which is equal to optimal.

##### *Model.lp:*
<br/>Representation of the Problem in Linear Programming context.

##### *clsp_-with-_lagrangian_relaxation.mst*
<br/>Solution of the Problem where:

Parameters | Number
-----------|--------
Items  	 | 10
Machines | 2
Periods  | 4


<br/>##### *Note*: The maximum case possible for the parameters has been provided. This is because CPLEX's community edition was used. 

*These results were obtained on a system with following configuration:*<br/>
_CPU    -> Intel Core i5 - 8285U @ 1.60GHz<br/>
Memory -> 8GB RAM<br/>
GPU    -> Nvidia Geforce MX150<br/>
VRAM   -> 2GB <br/>_
