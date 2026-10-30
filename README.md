# SQL-HA-DR

SQL Server high availability and disaster recovery scripts and notes, consolidated from separate repositories. Each folder is one former repo, with its full commit history preserved.

## Always On Availability Groups
| Folder | What it covers |
|---|---|
| [always-on-AG-related-commands](always-on-AG-related-commands) | Everyday AG commands and backup-preference checks |
| [Show-AG-PRIMARY-from-any-replica](Show-AG-PRIMARY-from-any-replica) | Find the current primary from any replica |
| [LIST-AG-databases](LIST-AG-databases) | List all AG databases |
| [AGlagforalert](AGlagforalert) | AG lag monitor: table, procedure and alerting |
| [AG-configuration-multi-subnet-and-single-subnet](AG-configuration-multi-subnet-and-single-subnet) | AG setup: automatic seeding, multi-subnet / multi-region |
| [DTC-and-Mirroring](DTC-and-Mirroring) | Clustered DTC for AGs and mirroring references |

## Failover Cluster Instances
| Folder | What it covers |
|---|---|
| [FCI](FCI) | FCI notes and unattended cluster installation docs |
| [SQL-FCI-and-Alwayson-AG](SQL-FCI-and-Alwayson-AG) | FCI combined with Always On AG |
| [AG-FCI-DNN-VNN-Load-Balancer](AG-FCI-DNN-VNN-Load-Balancer) | Step-by-step Azure build: VNet, availability set, VMs, cluster, DNN/VNN and load balancer, DR node |

## Log shipping
| Folder | What it covers |
|---|---|
| [LogShipping](LogShipping) | Log shipping setup (T-SQL and PowerShell), monitoring, status and removal |

## Replication
| Folder | What it covers |
|---|---|
| [Replication](Replication) | Replication monitoring scripts and troubleshooting (skipping errors, aliases) |
| [replication-reading](replication-reading) | Replication reading notes |
