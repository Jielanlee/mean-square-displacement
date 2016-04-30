# mean-square-displacement
These two scripts help obtain element-wise decomposed mean square displacement from a VASP Molecular Dynamics run reading the XDATCAR file. In a directory with XDATCAR, you should first run the xdarcar2xyz script and when it finishes, run the msd script. It should calculate the element-wise decomposed MSD. The first column of the output file is the MD step, and for each element, there will be 4 columns, first being the total element-wise MSD and the remaining three columns will be the MSD along lattice vectors a, b and c.

The scripts have been working fine for me (for vasp version 5 and later) but I highly recommend doing some tests to make sure it works for your system and the results are meaningful.

Update (April 2016): Please note that I made this set of old scripts available based on frequent requests in past. It is provided *as-is*, for those who need easy access to mean square displacement from VASP XDATCAR files. They are not comprehensive, and may lack documentation, but maybe adequate for many users.
