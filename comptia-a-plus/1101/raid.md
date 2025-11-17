# RAID
## RAID 0 Striping
- requires at least 2 drives
- evenly splits data
- high performance
- no redundancy
## RAID 1 Mirroring
- file blocks are duplicated between 2 or more physical drives
- high disk utilization (doubled)
- high redundancy
## RAID 5 Striping with Parity
- file blocks are striped (like RAID 0), along with a parity block
- requires at least 3 disks
- efficient use of disk space, since files aren't duplicated
- parity is spread across drives
- high redundancy
- parity calculation may effect performance
## RAID 10 (1+0) A Stripe of Mirrors
- the speed of striping, the redundancy of mirroring
- requires at least 4 drives

