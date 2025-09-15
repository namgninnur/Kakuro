# Kakuro

Looking to create an automated Kakuro Solver.

Key Steps
- DONE - Set up logic for available combinations for each array (Can be enhanced to be more concise)
- Create Board Set-up including N/A cells, free cells and sum cells (incl bi directional)
- Devise simple first level logic to fill cells
  - Only available option for each cell
  - Only option in that array for a required number
- Run this logic in a loop until Kakuro is solved or no further progress can be made based on current logic
- Implement second level logic (e.g. if a pair of cells in an array can only be that pair, remove that pair as available options for other cells in that array)
- Implement additional logic types as required to increase solve rate and speed e.g. area based logic
- Record solve status and time for each solver state over a base set of problems
- Iterate and enhance

Future Extensions
- Utilise AI computer vision to input the board
- Create an android app to capture images and solve locally
