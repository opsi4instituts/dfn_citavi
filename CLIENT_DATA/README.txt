The initial version of this package was created by Eric Esser, Wissenschaftszentrum Berlin für Sozialforschung (Berlin Social Science Center) and published at the DFN-Repository of the initiative OPSI4instituts: https://opsi.wzb.eu
Contact, questions and suggestions: eric.esser@wzb.eu / opsi@wzb.eu

HOWTO
-----
1. Install the package on the OPSI server on the command line by "opsi-package-manager -i -p ask dfn_citavi_<version/packagenumber>.opsi".
2. After the installation copy your Common.dat4 or Common.dat5 file with the licence information in the "custom" directory in the project folder of the product on the OPSI server and set the property type-of-license to site-license-file. 

PROPERTIES
----------
* desktopicon: Generate or delete desktop icon.
* custom-post-install: Define filename for include script in custom directory after installation.
* custom-post-deinstall: Define filename for include script in custom directory after deinstallation.
* type-of-license: Defines the type of license: "testversion" installs citavi as test version, "site-license-file" uses the Common.dat4 or Common.dat5 file placed in the custom folder of the package.

To see how to customize the MSI file for your institut, please visit:
http://www.citavi.com/sub/manual5/de/deploying_with_a_software_distribution_system.html
