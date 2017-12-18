# kc-plugins-master-list
This is the plugins list where publisher (developers or other interested parties) can publish scripts. At the moment this is a proof of concept. If someone wants to make an existing script installable through the related Installer script here is a short introduction:

No prerequisities beyond having a github account. No scripting, programming or even git skills needed. You don't even have to have any software installed on your machine, everything can be done by the github web UI.

First you write the .plugininfo xml file. Copy the template or one of the example files (ATM there's one short example). Edit to your liking. The script files to be installed must be available through url. ATM zipped projects are handled. You have to add the zip url to the xml file and the file names which will be installed from that zip.

You have to be added to the kc-plugin-publishers github organization and have rights to create branches etc. to this repo. Ask someone who can add you.

Then you can create a branch, add your plugininfo file there and create a pull request. All this can be done through the github web UI, even editing the file.

When the file is in a new branch you can test it for real. Run the installer. Set the master list zip file url to point to the branch instead of master. Set the to-be-installed script name. Install. Check if the script was installed correctly.

If it works you can merge the branch to master. And that's it.
