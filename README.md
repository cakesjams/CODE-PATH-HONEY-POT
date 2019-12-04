CodePath University's Web Security

# Project 9 - Honeypot

Time spent: **30** hours spent in total

- [x]	Milestone 0: To the Cloud!

- [x]	Milestone 1: Create MHN Admin VM

- [x] Milestone 2: Install the MHN Admin Application

- [x] Milestone 3: Create a MHN Honeypot VM

- [x] Milestone 4: Install the Honeypot Application

- [x] Milestone 5: Attack!


### Which Honeypot(s) you deployed
1. Dionaea with HTTP
2. cowrie


### Any issues you encountered
The hardest part was keeping MHN and the server stable enough to collect data. After a few days my honeypot would stop and return a 502 bad Gateway error message. Then it would terminate my SSH connection so I could not fix whatever happened which was really annoying.

### Attack Summary

**number of attacks:** 12 (because I had to re-deploy)

**Top 5 Attacker IPs:**
1. 80.211.180.23 (1 attacks)
2. 79.2.22.244 (1 attacks)
3. 112.217.225.59 (1 attacks)
4. 112.217.207.130 (1 attacks)
5. 46.43.49.90 (1 attacks)

**Top 5 Attacked Ports:**
1. 22 (15 times)

### Any unresolved questions raised by the data collected
None right now. This was very interesting assignment despite the instability of MHN

### References

[MHN](https://github.com/threatstream/mhn#installing-server-tested-ubuntu-12043-x86_64-and-centos-67 "MHN")

[gcp mhn instructions](https://github.com/RedolentSun/gcloud-instructions-for-mhn)
