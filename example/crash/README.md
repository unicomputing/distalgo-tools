#Usage
1. all processes should inherit class sim.Sim
2. call super().crash(procs) to crash procs, and
   call super().recover(procs) to recover
   
#A simple example, vrpaxos 
* vrpaxos.da is copied from https://github.com/DistAlgo/distalgo/blob/master/da/examples/vrpaxos/orig.da except that each class additionally inherits sim.Sim.
* tester.da puts the main function of orig.da in a Test class and adds calls to crash and recover.
* run tester.da to see the simulation
