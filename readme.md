## 1. Converting .mat to .hdf5 file format using older version of CLIMADA (v3.2.2)
The script used for this conversion is located in the custom/ folder.

Although the script folder originates from CLIMADA v6.0.1, the actual conversion must be run in an environment where the older CLIMADA version (v3.2.2) is installed, because the .mat to .hdf5 conversion relies on legacy functions or data structures that are compatible only with that version.

Any modifications made to the script files from the newer version (v6.0.1) to enable this process are documented in custom/updates.txt. This file serves as a changelog and includes details about which lines were altered, added, or removed to ensure backward compatibility for the conversion.


## 2. CLIMADA installation in Google Colab
The notebook files for setting up CLIMADA in Google Colab are available in the CLIMADA_installation_GCollab folder. Following are the two option to setup climada in google collab:
    -   Using pip : This approach clone the climada python package code from github and install the package
    -   Using conda : This option involves setting up conda inside the Colab session and installing the CLIMADA package.







