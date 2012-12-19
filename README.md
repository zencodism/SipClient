SipClient
=========

CSIPSimple fork with dependant projects

To build: 
0. Have Android SDK and NDK downloaded and (SDK) compiled.
1. Consult http://code.google.com/p/csipsimple/wiki/HowToBuild
2. Export pathes to NDK and SDK as link above suggests
3. Configure and make library (in CSIPSimple subdir configure, make, make install)
4. Build ActionBarSherlock subproject (android project update --target <TARGET_NUMBER> --path <YOUR PATH TO PROJECT>, ant debug)
5. Build CSIPSimple (same update as above, will create local.properties, then ant debug with default buildfile should run without problems.

Resulting apk is installable on your device. Enjoy.

(optional) 6. Download and install video plugin from http://nightlies.csipsimple.com/plugins/CSipSimpleVideoPlugin.apk
Perhaps that apk should be kept in repo as well.
