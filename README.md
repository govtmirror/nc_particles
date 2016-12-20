# nc_particles

Project for the documentation, discussion, and Examples of a standard for a netcdf format for particle tracking model results

This project contains:

### The project proposal:

[Read more words!](nc_particle_standard.md)

``nc_particle_standard.md``

### Example data files

One tiny sample for now, generated by a python script, and used for the test code.

``python_implementation/nc_particles/tests/sample.nc``

And one pretty small example, generated by the NOAA GNOME model:

``python_implementation/nc_particles/tests/boston_trajectory.nc``


### A Python package for code to Read/Write the format.

``python_implementation``

See the ``build_example.py`` script in the examples dir in the python package for how to write files.

And the ``boston_example.ipynb`` iPython notebook for example of how to read the files.


