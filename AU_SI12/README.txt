Scripts for downloading the following data set using wget:

AMSR-E/AMSR2 Unified L3 Daily 12.5 km Brightness Temperatures, Sea Ice Concentration, Motion & Snow Depth Polar Grids, Version 1
DATA SET ID: AU_SI12
DOI: 10.5067/RA1MIJOYPK3P


Data available at:
------------------
https://nsidc.org/data/au_si12/versions/1#anchor-1

Grid coordinates / cell area
----------------------------
url: https://nsidc.org/data/nsidc-0771/versions/1
data url: https://daacdata.apps.nsidc.org/pub/DATASETS/nsidc0771_polarstereo_anc_grid_info/
file: NSIDC0771_CellArea_PS_N12.5km_v1.0.nc
info: https://nsidc.org/data/user-resources/help-center/guide-nsidcs-polar-stereographic-projection

Download method
---------------
WGET

Download all dates (he5 file from date's folder only), no directory stucture:
---------------------
wget --load-cookies ~/.urs_cookies --save-cookies ~/.urs_cookies --keep-session-cookies --no-check-certificate --auth-no-challenge=on -r --reject "index.html*" --no-parent -nH --cut-dirs=3 -A he5 -e robots=off https://n5eil01u.ecs.nsidc.org/AMSA/AU_SI12.001/

Download just one date (he5 file from date's folder only), no directory stucture:
-------------------------
wget --load-cookies ~/.urs_cookies --save-cookies ~/.urs_cookies --keep-session-cookies --no-check-certificate --auth-no-challenge=on -r --reject "index.html*" --no-parent -nd -A he5 -e robots=off https://n5eil01u.ecs.nsidc.org/AMSA/AU_SI12.001/2012.07.02/

Download a specific file:
-------------------------
wget --load-cookies ~/.urs_cookies --save-cookies ~/.urs_cookies --keep-session-cookies --no-check-certificate --auth-no-challenge=on -r --reject "index.html*" -np -e robots=off https://n5eil01u.ecs.nsidc.org/AMSA/AU_SI12.001/2012.07.02/AMSR_U2_L3_SeaIce12km_B04_20120702.he5


