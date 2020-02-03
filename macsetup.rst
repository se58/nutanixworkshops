Setup for Mac
=============

Follow these steps to install Sphinx and Atom onto your MacBook.

Python
++++++
Before getting started Python must be installed on the computer. If you're not sure whether it's already installed:

- Open a Terminal Session

- Type in ``python --version`` and press [Enter]

If you don't see a version number returned then it will need installing, I recommend using the distributions from the `Python website`_.

.. _python website: https://www.python.org/downloads/mac-osx/


That's Python taken care of.


Pip
+++

To get the software packages installed please check if ``pip`` is installed, to do this:

- Type ``pip`` and press **[Enter]**

If you don't see a screen similar to this then it'll need installing.

.. image:: /images/mac-pip-01.png
  :width: 600

To install **pip** follow these simple steps:

- Type in ``curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`` and press **[Enter]**

.. image:: /images/mac-pip-02.png
  :width: 600

- Type in ``sudo python get-pip.py`` and press **[Enter]**

.. image:: /images/mac-pip-03.png
  :width: 600

Now, when you type in ``pip`` and press **[Enter]** you'll see a screenshot similar to the one at the beginning of this section.

Sphinx
++++++
The Python documentation tool official website is `here`_ however, there's no need to read the install instructions just follow the steps below.

.. _here: http://www.sphinx-doc.org/en/master/usage/installation.html

For simplicity the commands below are all that's needed to get the packages installed.

- Ensure you're internet connected

- Open a Terminal Session on your Mac

- Type in ``sudo pip install sphinx`` and press **[Enter]**

If after this first command you receive a warning stating the system path does not include /Users/*username*/Library/Python2.7 then jump to the end of this section follow the steps for **Updating Path** then return here. Re-run the first command then continue with the others.


- Type in ``sudo pip install sphinxcontrib-fulltoc`` and press **[Enter]**

- Type in ``sudo pip install sphinx-bootstrap-theme`` and press **[Enter]**

- Type in ``sudo pip install sphinx_fontawesome`` and press **[Enter]**


Installing Atom
+++++++++++++++
An editor is required and it's entirely your choice what to use. Atom links well with GitHub Desktop and that's what will be used in this tutorial.

- Open a web browser and head to ``https://atom.io/``

- Download and install the software (it's about 170mb)

.. image:: /images/mac-atom-01.png
  :width: 300

- You may need to move the application file from your Downloads directory to your Applications directory

.. image:: /images/mac-github-desktop-01.png
  :width: 300


- A package needs installing into Atom so select **Install a Package**

.. image:: /images/mac-atom-02.png
  :width: 300

- Type in ``github-plus`` and click **Install**

.. image:: /images/win-atom-03.png
  :width: 300

That's Atom complete.


Installing GitHub Desktop
+++++++++++++++++++++++++
A really good tool that interacts directly with GitHub, syncs repositories, highlights file differences and keeps it simple for launching Atom.

- Open a web browser and head to ``https://desktop.github.com/``

- Download and install the software (it's about 83mb)

- Now follow the steps in Launching **GitHub Desktop**

Updating Path
+++++++++++++
**ONLY** follow this if you've received an error installing Sphinx

- Type in ``vi .profile`` and press **[ENTER]**

- Press the letter ``i`` to place the editor into **Insert mode**

- Type in ``export PATH="/Users/your_username_directory/Library/Python/2.7/Bin:$PATH"``

- Press the ``ESC`` key

- Type in ``:``

- Type in ``wq`` and press **Enter**

- Close the current Terminal Session shell

The next time you launch a session the new path will be reflected
