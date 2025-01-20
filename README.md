I dedicate this repository to share the enhanced version of my calculator project.
The apps will be free to use, but I need something that I can call my "ownership" to the project, so I won't share the plain source code to each module or even the main scripts.
Everyone will be free to use the apps, but need my approval to access it each time. The approval request will send me a telegram notification and I will have to respond to approve or deny.

For now, the apps only consist of two calculator modules. Those are Imperfection Extractor and JONSWAP random wave generator.
The Imperfection Extractor module is usefull for onshore pipeline engineer to extract actual 'imperfection' to be identified and compared to allowable limit stated in upheaval buckling analysis
The JONSWAP random wave generator is intended to back-calculate known JONSWAP spectrum properties of wave data and create a set of individual random wave which possibly construct a simillar JONSWAP spectrum.
JONSWAP module is not yet verified. I haven't check how close JONSWAP spectrum constructed by each generated random data with given JONSWAP properties.

Future additions to the module will be shared in this repository and I'll ensure that the script will handle the update process for you.

IMPORTANT:
1. I suggest not to download the 1.00 version because that upload is only intended for beta testing
2. This apps require user to have python installed in the system, so make sure to install python first
3. All dependencies required to run this apps is already handled by main script, all you need to do is install python via command prompt (command: *pip install python*) and run "RZD_apps.pyc"
