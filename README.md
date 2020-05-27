# SCOM2007CUChecks
Scripts that check if CU rollups on SCOM 2007 have been correctly applied
These are the scripts for 2007R2 CU 5 and 6 and 7 and were moved from Technet Galleries to here.


This download contains a few scripts that test if CU7 was successfully applied to a SCOM 2007 R2 server. In January 2013 Microsoft release SCOM 2007 R2 CU7.

It contains scripts for the following roles:
Root management server
Management server
Gateway
Web Console

Refer to the following link for the reasoning behind this and the method of running the script and example output.

Checking if CU7 for SCOM 2007 R2 has been applied successfully

If you are looking for the same script for CU5, check back at the link above and it will guide you to the Gallery entry for CU5.

If you are looking for the same script for CU6, check back at the link above and it will guide you to the Gallery entry for CU6.

Note: These scripts do not check for every possible file which got changed, but it checks 90% of the regular files at least and the agent update files and log files and management pack versions. For instance it does not check in the language specific folder, because there are multiple possibilities there. Everything in the main binary folder does get checked though.

Enjoy!
Bob Cornelissen
