# DownloadNSIDC
Python notebooks for bulk downloads of data sets from the National Snow and Ice Data Center ([NSIDC](https://nsidc.org/home)). 
</br>Created for myself to save time, see world. But may be helpful for others using the same data!


Reference NSIDC's Guide for for Programmatic Data Access:
</br>https://nsidc.org/data/user-resources/help-center/programmatic-data-access-guide

:exclamation: Required initial step :exclamation:
</br> Store your Earthdata Login credentials for authentication in a .netrc file in your home directory (see [NSIDC instructions](https://nsidc.org/data/user-resources/help-center/programmatic-data-access-guide))


## [AE_SI12](https://github.com/mackenziejewell/DownloadNSIDC/tree/main/AE_SI12)

Wget scripts for downloading AMSR-E/Aqua Daily L3 12.5 km Brightness Temperature data (DATA SET ID: AE_SI12, DOI: [10.5067/AMSR-E/AE_SI12.003](https://nsidc.org/data/ae_si12/versions/3)). Also a notebook for locally cropping and resaving data to save disk space.

## [AU_SI12](https://github.com/mackenziejewell/DownloadNSIDC/tree/main/AU_SI12)

Wget scripts for downloading AMSR-E/AMSR2 Unified L3 Daily 12.5 km Brightness Temperatures (DATA SET ID: AU_SI12, DOI: [10.5067/RA1MIJOYPK3P](https://nsidc.org/data/au_si12/versions/1)). Also a notebook for locally cropping and resaving data to save disk space.
