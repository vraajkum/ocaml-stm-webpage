# ocaml-stm-webpage

We will implement and compare two software transactional memory (STM) systems for
Multicore OCaml: a lazy versioning + optimistic conflict detection system, partially modeled after
the TL2 algorithm, and an eager versioning + pessimistic conflict detection system modeled
after LogTM. We will build transactional data structures on top of each, benchmark both
against Domainslib mutex-based locks under varying contention, and perform a detailed
analysis of throughput, abort rates, and synchronization overhead to understand which
design wins and under what conditions.

## Project Proposal
[PDF](proposal.pdf)

## Milestone Report
[PDF](milestone_report.pdf)
