Scripts for downloading the following data set using wget:

AMSR-E/Aqua Daily L3 12.5 km Brightness Temperature, Sea Ice Concentration, & Snow Depth Polar Grids, Version 3
DATA SET ID: AE_SI12
DOI: 10.5067/AMSR-E/AE_SI12.003


Data available at:
------------------
https://nsidc.org/data/ae_si12/versions/3

Grid coordinates / cell area
----------------------------
url: https://nsidc.org/data/nsidc-0771/versions/1
data url: https://daacdata.apps.nsidc.org/pub/DATASETS/nsidc0771_polarstereo_anc_grid_info/
file: NSIDC0771_CellArea_PS_N12.5km_v1.0.nc
info: https://nsidc.org/data/user-resources/help-center/guide-nsidcs-polar-stereographic-projection

Download method
---------------
WGET

Download all dates (hdf file from date's folder only), no directory stucture:
---------------------
wget --load-cookies ~/.urs_cookies --save-cookies ~/.urs_cookies --keep-session-cookies --no-check-certificate --auth-no-challenge=on -r --reject "index.html*" --no-parent -nH --cut-dirs=3 -A hdf -e robots=off https://n5eil01u.ecs.nsidc.org/AMSA/AE_SI12.003/


Download just one date (hdf file from date's folder only), no directory stucture:
-------------------------
wget --load-cookies ~/.urs_cookies --save-cookies ~/.urs_cookies --keep-session-cookies --no-check-certificate --auth-no-challenge=on -r --reject "index.html*" --no-parent -nd -A hdf -e robots=off https://n5eil01u.ecs.nsidc.org/AMSA/AE_SI12.003/2002.06.01/


Download a specific file:
-------------------------
wget --load-cookies ~/.urs_cookies --save-cookies ~/.urs_cookies --keep-session-cookies --no-check-certificate --auth-no-challenge=on -r --reject "index.html*" -np -nH --cut-dirs=3 -e robots=off https://n5eil01u.ecs.nsidc.org/AMSA/AE_SI12.003/2002.06.01/AMSR_E_L3_SeaIce12km_V15_20020601.hdf
