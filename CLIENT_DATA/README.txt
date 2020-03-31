The initial version of this package was created by Eric Esser, Wissenschaftszentrum Berlin für Sozialforschung (Berlin Social Science Center) and published at the DFN-Repository of the initiative OPSI4instituts: https://opsi.wzb.eu
Maintainer is now Robert Stroetgen
Contact, questions and suggestions: r.stroetgen@tu-braunschweig.de

HOWTO
-----
1. Install the package on the OPSI server on the command line by "opsi-package-manager -i -p ask dfn_citavi_<version/packagenumber>.opsi".
2. After the installation copy your Common.dat6 file with the licence information in the "custom" directory in the project folder of the product on the OPSI server and set the property type-of-license to site-license-file. 

PROPERTIES
----------
* desktopicon: Generate or delete desktop icon.
* custom-post-install: Define filename for include script in custom directory after installation.
* custom-post-deinstall: Define filename for include script in custom directory after deinstallation.
* type-of-license: Defines the type of license: "testversion" installs citavi as test version, "site-license-file" uses the Common.dat4 or Common.dat5 or Common.dat6 file placed in the custom folder of the package.
* Citavi Admin Properties:
  * delete-user-settings-on-shutdown: Setting the value to 1 ("Always") means that the user settings are always deleted when Citavi is closed (even if the user remains logged in). The user will also be logged out every time Citavi is closed if this option is selected; Setting the value to 2 ("Never") means that user settings are never deleted when Citavi is closed (even if the user logs out); Setting the value to 0 ("Default") or no value means that the user settings will be deleted when users log out of their accounts.
  * disable-add-on-store: Setting the value to 'true' means that the Add-On Manager (Tools > Manage add-ons) and the online macros for the Citation Style Editor will be made invisible or blocked. The manual installation of add-ons by registry key will not be affected.
  * disable-auto-check-for-live-update: Setting the value to "true" means that Citavi is not allowed to check for automatic updates.
  * disable-ceip: Setting the value to 'true' means that no user data will  be send to Citavi
  * disable-citavi-account: Setting the value to "true" means that login into Citavi account is not possible
  * disable-welcome-screen: The first time they start Citavi 6, users will not see the Welcome Screen which helps them convert their projects from previous versions.

Citavi Admin Properties:
https://www1.citavi.com/sub/manual6/en/adminsettings.html

To see how to customize the MSI file for your institut, please visit:
https://www1.citavi.com/sub/manual6/de/deploying_with_a_software_distribution_system.html


