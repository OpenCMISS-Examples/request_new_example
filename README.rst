Request New Example
===================

A repository for creating issues that request a new example repository.

Process for getting a new repository created
--------------------------------------------

The following instructions provide guidance on how to get a new example repository created within this organisation where you do not have authority to do so:

#. Create a `new issue <https://github.com/OpenCMISS-Examples/request_new_example/issues/new>`_ on this repository.
#. In the issue:

   #. Specify the name for the new repository.
   #. Specify the license for the new repository that you would like.
  
If you do not specify a license for your new repository the Apache 2.0 license will be chosen by default.

When an issue is approved a new repository will be created by the organisation maintainers this will enable you to create a pull request against the new repository that will then be reviewed and subsequently (once review comments have been dealt with) merged in.

Process for creating first pull request
---------------------------------------

The following instructions are offered to provide guidance on the process required to make your first pull request against the new repository.  We will make the assumption that you are doing/going to be doing your work on the *develop* branch.

The first step of the process is to `fork <https://help.github.com/articles/fork-a-repo/>`_ the new repository to your own account.  If you have an existing example on your local disk then follow these instructions:

#. Open a terminal style application
#. cd /where/my/example/is # make the current directory the root directory of your example.

   - If this directory is **not** a git repository
   
     #. git init .

   - then

     #. git remote add origin <location of your forked git repository>

#. git add .
#. git commit -m "Commit message relevant to the changes made."
#. git push origin develop
     
**Note:** Replace <location of your forked get repository> with the actual location of the repository, the easiest way to do this is to navigate to your forked repository on GitHub and click the **Clone or Download** button.  Copy the clone URL of the repository and substitute this URL for <location of your forked get repository>

Now you should be able to create a new `pull request <https://help.github.com/articles/creating-a-pull-request-from-a-fork/>`_.

Adding New Example
==================

The following instructions are for the maintainers of this organisation who have authority to create new repositories within the OpenCMISS-Examples organisation:

#. Use the new button to add the new repository.
#. Assign a license to the repository, Apache 2.0 by default if not otherwise specified in the issue.
#. Create a branch 'develop' from 'master'.
#. Set the 'develop' branch as the default branch in the project settings.
