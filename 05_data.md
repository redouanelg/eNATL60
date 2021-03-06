# Access to eNATL60 data


 - The entire 3D outputs of both tide and non-tide simulations are permanently stored at CINES supercomputing center in Montpellier, France (https://www.cines.fr/). The 3D variables are stored in netcdf4 daily files, 1 file per variable : gridT, gridS, gridU, gridV, gridW, gridZ, the 2D variables are regrouped under gridT-2D, gridU-2D,gridV-2D, flxT and icemod. Some surface fields are also available in zarr format (ssh, ssu, ssv for both simulations), currently stored on HAL, the [CNES](https://cnes.fr) cluster
 
 - Some geographic or surface extractions are available on the MEOM-IGE group cluster ige-meom-cal1 and can be downloaded through opendap upon request, the main regions are:
     - GULFSTREAM
     - ACORES
     - OSMOSIS
     - WESTMED
     - LABRADOR
     - GIBRALTAR
 
 - The pangeo-cloud (https://catalog.pangeo.io/browse/master/ocean/MEOM_NEMO/) hosts the surface fields converted to zarr format, computation can be done on https://ocean.pangeo.io/
 
 - You can ask for your personnalised dataset at aurelie.albert(at)ocean-next.fr
 
