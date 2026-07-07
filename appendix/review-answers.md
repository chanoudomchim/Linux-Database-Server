# Appendix A: Review Question Answers

## Chapter 1: Enterprise Linux Database Server Architecture

1. Linux Administrators, Infrastructure Engineers, DevOps Engineers, System Engineers, Network Engineers, Cloud Engineers, instructors, and students.
2. Because the focus is deploying, securing, operating, monitoring, backing up, and troubleshooting database servers, not teaching application query development.
3. Ubuntu Server 24.04 LTS and Rocky Linux 9.
4. Direct Internet exposure increases the likelihood of unauthorized access, brute-force attempts, vulnerability scanning, and data compromise.
5. It provides a controlled administrative path that can enforce authentication, logging, MFA, and network restrictions.
6. `sudo systemctl status SERVICE_NAME`.
7. `sudo ss -tulpen`.
8. Full filesystems can stop writes, break checkpoints, interrupt replication, and cause outages.
9. Logical backups export database objects and data; physical backups copy database files using database-aware or storage-aware methods.
10. Off-host backups protect against server loss, disk failure, ransomware, and accidental local deletion.
11. Recovery Point Objective: the maximum acceptable amount of data loss measured in time.
12. Recovery Time Objective: the maximum acceptable time to restore service.
13. Expired certificates can break encrypted application connections, replication, monitoring, or administration.
14. It exposes Linux host metrics for Prometheus scraping.
15. They provide mandatory access control; disabling them removes a major containment layer and hides configuration problems.
16. It defines persistent filesystems and mount options applied during boot.
17. They allow stable service naming without exposing systems publicly and simplify certificate and application configuration.
18. Shared accounts reduce accountability and make audit trails unreliable.
19. Correlation helps distinguish service faults from CPU, memory, disk, network, or kernel-level causes.
20. Verify that intended sources can connect, unintended sources cannot connect, and rules persist across reboot when required.
