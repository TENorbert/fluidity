input: clean
	gmsh -2 src/2d_square.geo
	../../bin/gmsh2triangle --2d src/2d_square.msh

clean:
	rm -rf *.stat *.vtu *.node *.ele *.edge *_checkpoint.flml  *convergence* *.log-0 *.err-0 src/*.msh \
	matrixdump matrixdump.info
