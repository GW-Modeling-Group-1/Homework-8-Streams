# Homework 8 - Streams
## Due April 8

----
###  Instructions
For this assignment we will all start from the self check model but each group will be responsible for doing a different modification. Note that you only have to do the part that is assigned to your group not all three parts.


 - **Group 1**:  Modify the self check example to make it a steady state model and then explore the sensitivity of the model to the boundary condition heads and the heads in the river (this would probably be best done with a loop).
  - First systematically vary the two boundary condition heads. You can vary both heads together as well as create gradients across the domain by having one side be higher.  Make sure you explore head ranges that make the aquifer confined and unconfined.
  - Then explore changing the head in the river again systematically varying it across a range of values.  
   - Use the river leakage outputs in the water balance file to calculate how the water exchanges between the river and the aquifer change as a function of head
   - Compare the impact of changing heads in the river to changing boundary condition heads on your results.

- **Group 2**: Modify the self check example to simulate the river by treating as a time varying constant head boundary. To do this you will cut the domain in half so that it only goes from the center of the domain to the right boundary and add a time varying constant head boundary that follows the prescribed heads from our river boundary as the left boundary of the domain. Compare and contrast the results of this simulation to right half of the river simulation from the self check:
  - Calculate the differences in heads and the differences in storage between these two approaches.
  - Explain how these two approaches compare and explain why there would be differences between the two.
  - Repeat your analysis with at least two different boundary conditions and discuss the sensitivity of your results to the the heads you are using on the boundaries.

- **Group 3**: Modify the self check example to change the transient behavior:
  - First repeat the two transient time periods 10 times each
  - Next build on this to vary the constant head boundary conditions so that they have an oscillation of the same magnitude as the oscillation of the river heads.
  - Vary this oscillation so that it is in phase and out of phase with the river head oscillation
  - Compare your results, looking at the exchanges between the river and the rest of the domain and the head profiles.  
  - Evaluate how the impact of the river boundary condition compares to the constant head boundary condition by looking at the heads equidistant between the two.  


----
###  Submission Instructions
 - Each group will make one set of slides and one Jupyter notebook to explain your results and approach. Individual reports are not needed.  
 - One person should email me the submission for your group by the start of class next Thursday.
