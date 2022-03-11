# CS455 Module 2 PR2: Pseudorandom Number Generation  
Author: Georgiy Antonovich Bondar  

Go to https://keshakot.github.io/CS455_M2.PR2/ to play the game)

# Behaviors
Pseudorandom Level generation: Assets/Scripts/LevelGenerator.cs

# Description
1. Use the buttons in the game to place objects according to pseudorandomly generated coordinates   
2. Use the slider to change the coverage of the area (i.e. the density/number of objects placed within the area)   

# Notes
1. The Halton sequence should appear more evenly spread than the Random placement. Note however that the Halton sequence oft repeats the same placements between runs.   
2. The Poisson sequence adds mainly gauranteed separation of objects, using the same RNG as Random.   

