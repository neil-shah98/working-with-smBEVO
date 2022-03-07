# working-with-smBEVO
Working with smBEVO

Currently working on 2 Main tasks:
1. Automating the generation of parameters sigmaX and sigmaY
2. Improving the robustness of the algorithm


So far, we have tried to improve the robustness by systematically varying the segment from which we build out the rest of the levels. We did see variation in the results as a consequence, so now we are trying to implement a system which decides whether or not to "jump" to a different level based on majority votes
