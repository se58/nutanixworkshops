Setup for MS Windows
====================

Follow these steps to install Python (v3), Sphinx and Atom onto your Windows 10 machine.


Phython
+++++++
Before getting started Python must be installed on the computer. If you're not sure whether it's already installed:

- Open a Command prompt **with the Administrator privilege**

- Type in ``phython --version`` and press [Enter]

- If you don't see a response like this **SCREENSHOT** then it will need installing else, skip to the **Installing Sphinx** section

The next steps will install a local package manager that can retrieve the necessary pacakge(s) for python, this is called Chocolatey. To begin we'll use PowerShell, updating the local execution policy to accept 3rd party scripts and then download the software.


- Open a PowerShell command prompt using **Run As Administrator**

- Type in ``cd ~`` and press [Enter] to switch to your local user directory

- Type in ``Set-ExecutionPolicy -Scope CurrentUser`` and press [Enter]

- Type in ``RemoteSigned`` and press [Enter]

- Press the letter ``A`` to answer **Yes to All** and press [Enter]

You should see something similar to this:

.. image:: /images/win-python-01.png
  :width: 600

- Type in ``$script = New-Object Net.WebClient`` and press [Enter]

- Type in ``$script | Get-Member`` and press [Enter]

Like this:

.. image:: /images/win-python-02.png
  :width: 600

- Type in ``$script.DownloadString("https://chocolatey.org/install.ps1")`` and press [Enter]

Like this:

.. image:: /images/win-python-03.png
  :width: 600

- Type in ``iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex`` and press [Enter]

Like this:

.. image:: /images/win-python-04.png
  :width: 600

The output will resemble something similar to this:

.. image:: /images/win-python-05.png
  :width: 600

- Type in ``exit`` and press [Enter]

- Shutdown and restart Windows

- Open a PowerShell command prompt again using **Run As Administrator**

- Type in ``cd ~`` and press [Enter] to switch to your local user directory

- Type in ``choco install -y python3``

The output will resemble something similar to this:

.. image:: /images/win-python-06.png
  :width: 600


Excellent, that's the foundation laid down. Next up is Sphinx.

Installing Sphinx
+++++++++++++++++
Sphinx is the compiler to convert the RST files you'll be creating into HTML format so you can test your content before finalising and distributing.

- Open a Command prompt again using **Run As Administrator**

- Type in ``pip install -U sphinx`` and press [Enter]

The output will resemble something similar to this, ignore the message about the *pip* version:

.. image:: /images/win-sphinx-01.png
  :width: 600


Excellent, that's Sphinx installed.

Installing Atom
+++++++++++++++
An editor is required and it's entirely your choice what to use. Atom links well with GitHub Desktop and that's what will be used in this tutorial.

- Open a web browser and head to ``https://atom.io/``

- Download and install the software (it's about 180mb) remembering to use **Administrator privilege**

.. image:: /images/win-atom-01.png
  :width: 300

The installer will finish and prompt with this association question:

.. image:: /images/win-atom-02.png
  :width: 300

- Click ``Yes, Always``

- A package needs installing into Atom so select **Install a Package**

.. image:: /images/win-atom-03.png
  :width: 300

- Type in ``github-plus`` and click **Install**

.. image:: /images/win-atom-04.png
  :width: 300

That's Atom complete.


Installing GitHub Desktop
+++++++++++++++++++++++++
A really good tool that interacts directly with GitHub, syncs repositories, highlights file differences and keeps it simple for launching Atom.

- Open a web browser and head to ``https://desktop.github.com/``

- Download and install the software (it's about 87mb) remembering to use Administrator privilege
