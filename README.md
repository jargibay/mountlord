mountlord 
This is written as a utility to handle NFS mounts in OS X using DSCL.

This was written originally as a wrapper script to help puppet manage NFS mounting in OS X, using the proper OS X way.
Ultimately it became a small command line utility/front end for doing network mounts with DSCL.

This was written for a specific case and does not necessarily work in all configurations.

Licensed under LGPL.

Written in BASH


Having this auto mount once configuration is set, you can create a plist file to run mountlord auto to ensure the network mount is reachable and the mountpoints exist, if not to create them
