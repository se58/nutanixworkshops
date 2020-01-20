Setup for MS Windows
====================

Follow these steps to install Sphinx and Atom onto your Windows 10 computer.


Phython
+++++++
Before getting started Python must be installed on the computer. If you're not sure whether you have it present:

#   Open a Command prompt **with the Administrator privilege**

#   Type in ``phython --version`` and press [Enter]

#   If you don't see a response like this **SCREENSHOT** then it will need installing else, skip to the **Installing Sphinx** section

The next steps will install a local package manager that can retrieve the necessary pacakge(s) for python, this is called Chocolatey (no idea why). To begin we'll use PowerShell, updating the local execution policy to accept 3rd party scripts and then download the software.


#   Open a PowerShell command prompt using **Run As Administrator**

#   Type in ``cd ~`` and press [Enter] to switch to your local user directory

#   Type in ``Set-ExecutionPolicy -Scope CurrentUser`` and press [Enter]

#   Type in ``RemoteSigned`` and press [Enter]

#   Press the letter ``A`` to answer **Yes to All** and press [Enter]

#   






Installing Sphinx
+++++++++++++++++
#   Open a web browser

#   Click this `link_` to open the Phython Doc Generator webpage

#   Scroll down to the **Windows** section



.. _this link: http://www.sphinx-doc.org/en/master/usage/installation.html








For simplicity the commands below are all that's needed to get the packages installed.

#   Open the link to Sphinx Doc Generator page Ensure you're internet connected

#   Open a Command prompt **with the Administrator privilege**

#   Type in ``sudo pip install sphinx`` and press **[Enter]**

#   Type in ``sudo pip install sphinxcontrib-fulltoc``
