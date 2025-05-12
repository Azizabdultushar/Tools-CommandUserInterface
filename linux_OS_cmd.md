# to remove the a tool: if it was a specific file like petalinux-v2019.run check the directory(where it was installed) simply remove the dir.
# to find out the installation directory = search its main script
$ find ~ -type f -name "settings.sh"
$ mkdir -p package # always use -p, because it the dir is exist then it will not make any dir.

