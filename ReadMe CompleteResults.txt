README – CompleteResults.xlsx

This file presents the complete performance results obtained for all 360 instances of the Green Permutation Flowshop Scheduling Problem with Sequence-Dependent Setup Times (GPFSPSDST).

=== File Structure ===

Each row of the spreadsheet corresponds to a result from a specific instance, solved by one of the evaluated methods.

The columns are organized as follows:

1. **Setup Group (s):** Indicates the group based on setup time intensity. Four groups are considered:  
   - 10 (SDST10)  
   - 50 (SDST50)  
   - 100 (SDST100)  
   - 125 (SDST125)

2. **Instance Number:** Identifies the specific instance (from 1 to 90) within each setup group.

3. **Instance Configuration:** Shows the number of jobs and machines used in the instance.  
   Example: “20x5” indicates 20 jobs and 5 machines.

4. **Method:** Name of the algorithm or heuristic method used to solve the instance.  
   Examples: `NEHT-RB`, `NEHT-RB+ES`, `NEHT-RB+VND+ES`, etc.

5. **Computational Time (s):** Time taken to solve the instance, in seconds.

6. **R-measure:** A quality indicator used to evaluate the performance of the approximated Pareto front.

7. **Hypervolume (10⁶):** Represents the hypervolume indicator (scaled by 10⁶), measuring the quality of the solution set in terms of convergence and diversity.

8. **Number of Solutions (NS):** Total number of non-dominated solutions found.

9. **Purity:** Measures how pure the solutions are in terms of belonging to the reference Pareto front.

10. **Dr:** Indicates the proximity of solutions to the reference front (lower is better).


