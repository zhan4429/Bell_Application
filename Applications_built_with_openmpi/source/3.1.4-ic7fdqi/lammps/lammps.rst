.. _backbone-label:

Lammps
==============================

Description
~~~~~~~~
LAMMPS stands for Large-scale Atomic/Molecular Massively Parallel Simulator. This package uses patch releases, not stable release. See https://github.com/spack/spack/pull/5342 for a detailed discussion. Note that in this installation serial and parallel versions of LAMMPS are provided by the same executable 'lmp' (there is no separate 'lmp_mpi').

Versions and Dependencies
~~~~~~~~
- 20200721
   #. fftw/3.3.8
   #. intel-mkl/2019.5.281
   #. openmpi/3.1.4

- 20201029
   #. fftw/3.3.8
   #. intel-mkl/2019.5.281
   #. openmpi/3.1.4

Module
~~~~~~~~
You can load the modules by::

    module load lammps

