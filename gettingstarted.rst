Working with Content
====================
Due to the nature of this topic there can't be a step-by-step guide as there's way too much that could be documented. Instead, here are some common approaches I follow that I've found comfortable to with. They may not be the most expedient but they do work.


Creating your own content
+++++++++++++++++++++++++
A simple few guidelines I follow when I create my own content:

- Create a new repository in GitHub via the website

- Launch **GitHub Desktop** and use the **Clone from Repository** supplying the **URL**

- From here I use Atom for content creation and GitHub Desktop to push the changes to the repository


Adapting Content
++++++++++++++++
If you've found a repository that contains a lot of what you're looking for but you'd like to customise for your own region, new screenshots, new features, etc... then I'd follow these steps:

- Create a new repository in GitHub via the website

- Launch **GitHub Desktop** and use the **Clone from Repository** supplying the **URL** (now both sides are in sync)

- I'd locate the repository I'm want to adapt and **Clone to a ZIP** file and then extract into my local computer into the directory where my files are

In the screenshot here you can see the option to **Download ZIP** file

.. image:: /images/clone-url.png
  :width: 300

- Now I can use GitHub Desktop to manage the push

|

.. note:: Don't forget that you should ideally have the **.gitignore** file in the root of the repository, this prevents the uploading of unnecessary operating system files.
