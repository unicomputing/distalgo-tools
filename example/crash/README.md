#Usage
1. all the processes need to inherit sim.Sim class
    * call super().crash(procs) to put procs to crash
    * call super().recover(procs) to recover
2. a simple example, vrpaxos
    * the vrpaxos.da is exactly the code from distalgo example except each class additionally inherits the sim.Sim class.
    * the tester.da copies everything in main function of the vrpaxos.da to a Test class which also inherits the sim.Sim class and added the statement of crash and recover.
    * run tester.da to see the simulation