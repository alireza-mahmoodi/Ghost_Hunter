# Ghost Hunter

This is a project about inference implementation for ghost tracking. I used Bayes Nets to implement algorithms for performing both exact and approximate inference. 

# Visual Depiction of the End Result

In the following, we can see the end result of the implementation in the Pacman world. The goal is to hunt down scared but invisible ghosts. Pacman is equipped with sonar (ears) that provides noisy readings of the Manhattan distance to each ghost.

The blocks of color indicate where each ghost could possibly be, given the noisy distance readings provided to Pacman. The numbers in the bottom of the screen show the noisy distance which are within 7 of the true distance. Pacman uses greedy strategy to hunt down ghosts as it believes each ghost is in its most likely position.

__NOTE:__ Pacman can't see the ghosts. The ghosts are only visible to us.

![](visual_demonstration/hunter_pacman.gif)
