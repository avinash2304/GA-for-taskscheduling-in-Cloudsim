# taskscheduling
test the taskscheduling using genetic algorithm 

Before submitting cloudlets, Broker can assign cloudlets to virtual machines, which is a NP-hard problem.
Hence, Genetic algorithm can be used to create the binding relationship.

Components of Cloudsim being used (Note, no power is considered):
1. Cloudlets
2. Broker: datacenterbroker
3. Datacenter: vmallocationpolicy
4. Host: vmscheduler
5. Vm: utilizationmodel