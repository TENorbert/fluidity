input: clean
	gmsh -3 -o column.msh src/column.geo
	../../bin/gmsh2triangle column.msh

clean: 
	rm -f  *.ele *.edge *.node *.face *.poly *.vtu *.s  *.stat *.log-0 *.err-0 matrixdump* *log *err
	rm -f *.msh
