# test
this is a test project

# Decompress with given decompressor when input file has given extension
# The command given must act as a filter.
#
.gz		/usr/bin/gunzip -c
.bz2		/usr/bin/bzip2 -c -d
.lzma		/usr/bin/unlzma -c -d
.z		
.Z		/bin/zcat
.F		
.Y		
#
# Enable/disable makewhatis database cron updates.
# If MAKEWHATISDBUPDATES variable is uncommented
# and set to n or N, cron scripts 
# /etc/cron.daily/makewhatis.cron
# /etc/cron.weekly/makewhatis.cron
# will not update makewhatis database.
# Otherwise the database will be updated.
