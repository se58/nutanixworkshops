Test it Out
===========
So you've written some lines of text and now want to see how it looks in a browser before publishing? For Mac and Windows it's very similar although they are documented separately.

Follow these steps:

Mac
+++
- Open a Terminal Session

- Change into the directory of the local copy of the repository

- Issue the command ``sphinx-build . testhtml`` and press **[Enter]**. This will create a sub-directory called **testhtml** and place the HTML compiled files into it.

- Review the output of the compile and fix errors

- Use Finder to navigate to the **testhtml** directory you just created

- Double click the ``index.html``, this will launch your web browser and show you the landing page of your site

Windows
+++++++
- Open a Command prompt **with the Administrator privilege**

- Change into the directory of the local copy of the repository

- Issue the command ``sphinx-build . testhtml`` and press **[Enter]**. This will create a sub-directory called **testhtml** and place the HTML compiled files into it.

- Review the output of the compile and fix errors

- Use Windows Explorer to navigate to the **testhtml** directory you just created

- Double click the ``index.html``, this will launch your web browser and show you the landing page of your site


.. note :: You may find that the local cached copies of pages in the web browser can cause confusion.  If you makes updates that don't show up I recommend closing the web page down, deleting the local **testhtml** directory and compiling it again.
