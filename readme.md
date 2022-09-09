Save packages for future use:

conda list --export > package-list.txt

Reinstall packages from an export file:

conda create -n myenv --file package-list.txt

