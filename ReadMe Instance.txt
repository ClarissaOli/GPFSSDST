README – Instance Structure for the GPFSPSDST

Contains 360 instances for the Green Permutation Flowshop Scheduling Problem with Sequence-Dependent Setup Times (GPFSPSDST). These instances are organized into four groups based on setup time intensity

- SDST10
- SDST50
- SDST100
- SDST125

Each group contains 90 instances, subdivided into 9 subgroups of 10 instances each. The complexity increases progressively

- Instances 1–30 20 jobs
- Instances 31–60 50 jobs
- Instances 61–90 100 jobs

Each job configuration is tested with
- 5 machines
- 10 machines
- 20 machines

=== File Format ===

Each instance file (.txt) follows the structure below

1. Line 1 Number of jobs (n)
2. Line 2 Number of machines (m)
3. Lines 3 to (2 + n) Processing times matrix (n rows, m columns)
4. Following lines m setup time matrices of size n × n (one for each machine)
   - Each matrix is composed of n lines, each with n columns
