# Onset-of-solid-state-mantle-convection-and-mixing-during-magma-ocean-solidification
Maxime MAURICE - maxime.maurice@dlr.de - 02/28/2017

This document contains captions for the data sets S1 to S168.  All the data sets are ASCII files containing the final
(i.e.  after 11 Myr) temperature and composition fields, the shrinking factor of all advected tracers mapped both at
their final and initital positions,  and  the  time  series  for  the  RMS  shrinking  factor  and  the  laterally-averaged
bottom Nusselt number.  Each file is named after the case it represents using the following convention: 
’B’ + buoyancy ratio (18 for 1.8 and 02 for 0.2) + ’Ra’ + log(Ra) + ’CT’ + t_MO (01 for 0.1 Myr, 1 for 1 Myr and 10 for 10 Myr).
The batch crystallization cases are written with ’Ba’ + ...  instead of ’B’ + buoyancy ratio + ...  .
For example:  B18Ra10CT01 indicates a case of fractional crystallization with B = 1.8, Ra  =  10^10 and t_MO =  0.1  Myr,
while  BaRa7CT01  a  batch  crystallization  case  with Ra = 10^7 and t_MO = 0.1.

# TEMPERATURE
Final temperature fields for all the presented simulations. These are ASCII files structured in three columns;
the first column contains the values of the temperature for each grid cell, the second column the x-coordinates
of the corresponding grid cells and the third column the y-coordinates.

# BOTTOM NUSSELT NUMBER
Time series of the laterally-averaged bottom Nusselt number for all the presented simulations. These are ASCII files 
structured in two columns; the first column contains the values of the laterally-averaged bottom Nusselt number for each
output time and the second the corresponding non-dimensional time.

# COMPOSITION
Final composition fields for all the presented simulations of the fractional crystallization case. These are ASCII files
structured in three columns; the first column contains the values of the composition for each grid cell, the second column
contains the x-coordinates of the corresponding grid cells and the third column contains the y-coordinates.

# SHRINKING FACTOR
Final shrinking factor values for all advected tracers mapped at their final positions, for all the presented simulations
of the fractional crystallization case. These are ASCII files structured in three columns; the first column contains the values
of the shrinking factor for each tracer, the second column contains the final x-coordinates of the corresponding tracer and the
third column contains the final y-coordinates.

# SHRINKING FACTOR 0
Final shrinking factor values for all advected tracers mapped at their initial positions, for all the presented simulations of
the fractional crystallization case. These are ASCII files structured in three columns; the first column contains the values of
the shrinking factor for each tracer, the second column contains the initial x-coordinates of the corresponding tracer and the
third column contains the initial y-coordinates.

# RMS SHRINKING FACTOR
Time series of the RMS shrinking factor for all the presented simulations of the fractional crystallization case. These are
ASCII files structured in two columns; the first column contains the values of the RMS shrinking factor for each output time
and the second the corresponding non-dimensional time.
