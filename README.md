# Software Transactional Memory for Multicore OCaml

We implemented two software transactional memory (STM) systems for Multicore OCaml from
scratch and evaluated them against the production kcas library and a standard-library Mutex
baseline on the GHC lab machines. We benchmarked the systems across 1 to 8 OCaml domains on
four transactional data structures: a shared counter, a hash map, a linked list, and a bank account.
Both STM designs trailed kcas and Mutex by a significant margin on high-contention workloads,
and EP-STM exhibited substantially higher abort rates than LO-STM at moderate domain counts,
but we observed relative throughput depends heavily on the read/write ratio.

## Project Proposal
[PDF](proposal.pdf)

## Milestone Report
[PDF](milestone_report.pdf)

## Final Report
[PDF](final_report.pdf)
