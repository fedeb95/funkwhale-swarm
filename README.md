# funkwhale-swarm
Docker compose file onfigured to be run in a docker swarm 

This is configured to run all services depending on volumes on manager node, and workers on other nodes. For this to be working, S3 bucket has to be used for music storage (otherwise everything would be on manager).

Tested on three EC2 instances in a docker swarm.
