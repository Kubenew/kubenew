### Hi there 👋

This makes it easier to work with multiple clusters from the same machine.
To install the plugin, download the kubectl-ctx file and save it in any directory that is in your PATH:

curl -O https://raw.githubusercontent.com/Kubenew/kubenew/cubectl-cx
Then, make the kubectl-ctx file executable:

chmod +x kubectl-ctx
Now, you can verify that the plugin is correctly installed by running the following command:

kubectl plugin list
This lists all the plugins that kubectl detected, and the kubectl-ctx plugin should now be listed there.

To uninstall the plugin, simply delete the kubectl-ctx file.

