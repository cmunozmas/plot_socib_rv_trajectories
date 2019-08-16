# plot_socib_rv_trajectories
The plot_socib_rv_trajectories is a python notebook developed at SOCIB to plot the trajectiories from data collected by a VM-ADCP, thermosalinometer, GPS and weather station mounted onboard the RV-SOCIB. They are able to plot the trajectories of the main variables  stored into the SOCIB netcdf files and plot them on a map

## Prerequisites:

    Python libraries required: netCDF4, matplotlib, numpy, basemap, os and math
    
## The following features are already implemented in the notebook:

    Load netCDF variables module.
    Plot GPS trajectory (able to plot it from GPS, thermosal aor VM-ADCP).
    Plot temperature and salinity trajectory from thremosalinometer.
    Plot wind speed and direction from weather station.
    

## The following features are planned or in development:

    Improve wind speed and direction quiver plot.
    Add water current speed and direction quiver plot for VM-ADCP data.

## Copyright

Copyright (C) 2013-2019 ICTS SOCIB - Servei d'observació i predicció costaner de les Illes Balears http://www.socib.es

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program. If not, see http://www.gnu.org/licenses/.
