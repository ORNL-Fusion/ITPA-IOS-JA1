============
Equilibrium
============

Time
----

``equilibrium.time[:]`` |br|

Global
------

``equilibrium.vacuum_toroidal_field.r0`` |br|
``equilibrium.vacuum_toroidal_field.b0`` |br|


``equilibrium.time_slice[itime].global_quantities.ip`` |br| 
``equilibrium.time_slice[itime].global_quantities.psi_axis`` |br|
``equilibrium.time_slice[itime].global_quantities.psi_boundary`` |br|


1-D profiles
------------

``equilibrium.time_slice[itime].profiles_1d.rho_tor_norm[:]`` |br|  
``equilibrium.time_slice[itime].profiles_1d.psi[:]`` |br|
``equilibrium.time_slice[itime].profiles_1d.f[:]`` |br|   
``equilibrium.time_slice[itime].profiles_1d.f_df_dpsi[:]`` |br|  
``equilibrium.time_slice[itime].profiles_1d.dpressure_dpsi[:]`` |br|        
``equilibrium.time_slice[itime].profiles_1d.pressure[:]`` |br|    
``equilibrium.time_slice[itime].profiles_1d.q[:]`` |br| 


2-D profiles
------------

``equilibrium.time_slice[itime].profiles_2d[:].grid_type.index`` |br| 
``equilibrium.time_slice[itime].profiles_2d[:].grid.dim1[:]`` |br| 
``equilibrium.time_slice[itime].profiles_2d[:].grid.dim2[:]`` |br| 
``equilibrium.time_slice[itime].profiles_2d[:].psi[:, :]`` |br|  


Plasma boundary
---------------

``equilibrium.time_slice[itime].boundary.outline.r[:]``
``equilibrium.time_slice[itime].boundary.outline.z[:]``

.. |br| raw:: html

      <br>
