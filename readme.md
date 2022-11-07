Given an integer array nums, return all the triplets [nums[i], nums[j], nums[k]] such that i != j, i != k, and j != k, and nums[i] + nums[j] + nums[k] == 0.

Notice that the solution set must not contain duplicate triplets.

 INPUT              | OUTPUT                  |     EXPLANATION
 -------------------|-------------------------|--------------------------------
 [0,1,1]            | []                      | The only possible triplet does not sum up to 0.
 [0,0,0]            | [[0,0,0]]               | The only possible triplet sums up to 0
 [0,1,-1]           | [[0,1,-1]]              | The only possible triplet sums up to 0
 [0,1,2,-1,-2]      | [[0,1,-1],[0,2,-2]]     | The triples [0,1,-1] and [0,2,-2] sum up to 0.
 [-1,0,1,2,-1,-4]   | [[-1,-1,2],[-1,0,1]]    | The triplets [-1,-1,2] and [-1,0,1] are unique.



Constraints:

3 <= nums.length <= 3000
-105 <= nums[i] <= 105