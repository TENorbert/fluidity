input:	clean
	../../bin/gmsh2triangle --2d src/MMS_A.msh
	../../bin/gmsh2triangle --2d src/MMS_B.msh
	../../bin/gmsh2triangle --2d src/MMS_C.msh
	../../bin/gmsh2triangle --2d src/MMS_D.msh

clean:
	rm -f *.vtu *.stat *.s *.log *.node *.ele *.edge *checkpoint*
	rm -f *.err-? *.log-? \
	matrixdump matrixdump.info
