# scripts
# Some rsync scripts that are tested and working

# rsync backup of the data files at my MacOS system to a local Drobo -drobo02- system, using the ideas and instrucions in http://troy.jdmz.net/rsync/index.html with rsync and ssh with no passwd.

# The local Drobo is running a rsync installed from https://github.com/droboports/rsync
#
# To send a Dobo, which has a limited CPU power, from workstation rsync should go with compression 
# rsync -ahz [files]
# to recover from Drobo it works better to do it without compression
# rsync -ah [files]
