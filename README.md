# InstantInsanity_CombinatorialAlgorithmsProject
This is a Combinatorial Algorithms project which finds an answer or answers of a Instant Insanity Puzzle.
The Instant Insanity Puzzle consists of n slices that could be “pizza shaped” or “cube shaped”. 
The main difference between them is that the Pizza Instant Insanity has 5 faces, and the Cube Instant Insanity has 6 faces.
A triangular pizza slice has three sides, top and bottom. A cube has 4 sides, top and bottom.
When the slices are stacked in a tower, the top face and the bottom face of the slice are not being used.
The goal of the puzzle is finding a combination of slices without any duplicate of number in one column(pizza tower has 3 columns, and cube tower has 4 columns).
When finding a solution, rotating the slice is allowed but flipping the slice is not allowed.
For example, 1 2 3 is the shape of a slice. At the left of the slice, 1 is written, at the right of the slice, 2 is written, and at the bottom, 3 is writte. By rotating it clock-wise, 3 1 2 becomes the new shape of the slice, and by rotating it again, 2 3 1 becomes the new shape.
However, by flipping a 1 2 3 slice, the shape of the slice becomes 2 1 3, which can never be made by rotating the initial shape of the slice.
Also, I provided a flip solution of the puzzles only if the puzzle has no solution by rotating the slices.

The second part of the project is finding a Minimal Obstacle of a puzzle which is the set of slices that is never the part of a solution.
For example, a Minimal Obstacle of size 6 has No Solution only when those slices are stacked, which means that the stack of any of those 2 to 5 slices should have at least one solution.
