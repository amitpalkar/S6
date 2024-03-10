# S6
## Description
This Directory Contains the assignments for Session 6 (Backpropagation and Advanced Architectures) for
the course ERA-V2.

### Part 1
**File name**: 
  - **S6_BackProgation_AmitPalkar**
      - Below Image with learning Rate equal to 1.
        ![image](https://github.com/amitpalkar/S6/assets/160306763/86bc5f04-6f13-45ac-bef4-195bb9d60bd2)
      - Below Image with learning Rate equal to 2.
        - As can be seen from the image, the algorithm has converged rapidly (in about  50 iterations)
        ![image](https://github.com/amitpalkar/S6/assets/160306763/93f5b24d-c1a2-4e19-8c80-e2d9be9b8b5a)
      - Below Image with learning Rate equal to 0.1.
        - As can be seen from the image, the algorithm has not converged (after 105 odd iterations).
          i.e. the net Error has not down to zero.
        ![image](https://github.com/amitpalkar/S6/assets/160306763/6962ba39-77c6-4858-a08c-5db500ee2de6)
      - Below Image with learning Rate equal to 0.2
        - As can be seen from the image, the algorithm has not converged (after 105 odd iterations).
          i.e. the net Error has not down to zero.  However the convergence is slight better than learning
          rate of 0.1
          ![image](https://github.com/amitpalkar/S6/assets/160306763/12cb64fb-a598-42a8-9bfe-3318ef6635ca)
      -  Below Image with learning Rate equal to 0.5
         - As can be seen from the image, the algorithm convergence rate has improved with a bigger step size
           (or learning rate) as compared to 0.2.  However the net Error has not reduced to zero (after 105
           odd iterations).
          ![image](https://github.com/amitpalkar/S6/assets/160306763/39913c60-9ade-4c0b-b9f1-5dcf687ad057)
      - Below Image with learning Rate equal to 0.8
        - As can be seen from the image, the algorithm has almost converged.  However the net Error has not
          reduced to zero (after 105 odd iterations) as can be seen from the figure.
          ![image](https://github.com/amitpalkar/S6/assets/160306763/0334ad76-441b-4f43-9259-c7712978cebc)
  - **Brief Explanation of BackProgpation Algorithm**
       - The BackProgpogation Algorithm (also known as steepest gradient) is based on dynamically adapting
         the weights in the neural net by minimizing the total error square to zero.  This is done by
         differentiation of the net Error (which is a function of all weights in the network) to zero.
         The differential is done is a partial differentiation (dabba).
       - The learning rate (step size) determines the rate of convergence of the algorithm. Higher the step
         size higher is the rate of convergence however too high a step size may result in the algorithm
         not converging.
       - To avoid the algorithm in getting in local minima, sometimes a small jitter (noise) is added for
         the algorithm to come out of local minima.

        

 
