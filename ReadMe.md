# Utils

#FromNetGenToVTK_surface: 
Rebuilds the grid file in neutral Netgen format. grid --- surface divided into triangle.
Warning: the line with the number of cells by volume (i.e. 0) should be deleted from the source file

#FromNetGenToVTK_volume: Rebuilds the grid file in neutral Netgen format. 
grid --- volume divided into tetrahedra.

#FromVtkToDirection:rebuilds the sphere direction into 3d normalized vectors. The center of the triangle on the sphere is selected for the direction

#GetAverageSize: returns the average volume of all grid cells

#Make1dSolveAndTrace: one-dimensional projection of the solution on the selected direction. The projection includes the trace result