input: clean
	cd mesh; gmsh -2 np_rectangle.geo; ../../../bin/gmsh2triangle -s np_rectangle.msh; 

clean:
	rm -f  fluidity.* *.ele *.face *.node *.vtu *.poly *.edge *.s *.d.1 *.stat \
	matrixdump matrixdump.info
	rm -f mesh/*.msh mesh/*.edge mesh/*.ele mesh/*.node mesh/*.halo
	rm -f *flredecomp.flml
