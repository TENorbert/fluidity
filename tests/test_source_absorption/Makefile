input: clean
	gmsh -3 fluid_mesh.msh src/fluid_mesh.geo
	../../bin/gmsh2triangle fluid_mesh.msh 

clean:
	rm -rf *.halo *.c* *.s* *.vtu *.log *.node *.ele *.edge *.face *.vtu matrixdump* *.pyc *.msh fluidity.* Implicit*
	rm -rf solidmesh.Y3Dh0 solidmesh0* Ytmp
