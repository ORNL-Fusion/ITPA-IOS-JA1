=============
Core profiles
=============

Grid
----


``core_profiles.time`` |br|
``core_profiles.profiles_1d[itime].grid.rho_tor_norm[:]`` |br|
``core_profiles.profiles_1d[itime].grid.volume[:]`` 


Electron
--------

``core_profiles.profiles_1d[itime].electrons.density[:]`` |br|
``core_profiles.profiles_1d[itime].electrons.temperature[:]`` |br|
``core_profiles.profiles_1d[itime].electrons.pressure[:]`` |br|
``core_profiles.profiles_1d[itime].electrons.pressure_thermal[:]`` |br|

Ion
---

``core_profiles.profiles_1d[itime].ion[ispec].label`` |br|
``core_profiles.profiles_1d[itime].ion[ispec].element[:].a`` |br|
``core_profiles.profiles_1d[itime].ion[ispec].element[:].z_n`` |br|
``core_profiles.profiles_1d[itime].ion[ispec].density[:]`` |br|

**Thermal**

``core_profiles.profiles_1d[itime].ion[ispec].density_thermal[:]`` |br|
``core_profiles.profiles_1d[itime].ion[ispec].temperature[:]`` |br|
``core_profiles.profiles_1d[itime].ion[ispec].pressure_thermal[:]`` |br|

**Fast ion**

``core_profiles.profiles_1d[itime].ion[ispec].density[:]`` |br|
``core_profiles.profiles_1d[itime].ion[ispec].density_fast[:]`` |br|
``core_profiles.profiles_1d[itime].ion[ispec].pressure_fast_parallel[:]`` |br|
``core_profiles.profiles_1d[itime].ion[ispec].pressure_fast_perpendicular[:]`` |br|


**Total**

``core_profiles.profiles_1d[itime].pressure_ion_total[:]`` |br|
``core_profiles.profiles_1d[itime].pressure_parallel[:]`` |br|
``core_profiles.profiles_1d[itime].pressure_perpendicular[:]`` |br|
``core_profiles.profiles_1d[itime].pressure_thermal[:]`` |br|

.. |br| raw:: html

      <br>