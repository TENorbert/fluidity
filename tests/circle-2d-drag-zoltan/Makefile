input: clean
	../../bin/gmsh2triangle -2 src/circle-serial.msh
	../../bin/gmsh2triangle -2 src/circle-parallel.msh

clean:
	rm -f *.halo *.ele *.edge *.face *.node *.poly *.vtu *.pvtu *.s *.d.* *.stat *.s *.log-0 *.err-0
	rm -rf circle-2d-drag-parallel_? circle-2d-drag-parallel-adaptive_? \
	matrixdump matrixdump.info
	rm -rf *flredecomp*
