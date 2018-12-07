#Usage
1. all the processes need to inherit sim.Sim class
    * call super().crash(procs) to put procs to crash
    * call super().recover(procs) to recover
2. a simple example, vrpaxos