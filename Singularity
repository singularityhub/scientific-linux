# Copyright (c) 2015-2016, Gregory M. Kurtzer. All rights reserved.
# 
# "Singularity" Copyright (c) 2016, The Regents of the University of California,
# through Lawrence Berkeley National Laboratory (subject to receipt of any
# required approvals from the U.S. Dept. of Energy).  All rights reserved.

BootStrap: yum
OSVersion: 7
MirrorURL: http://ftp.scientificlinux.org/linux/scientific/%{OSVERSION}x/$basearch/os/
Include: yum


%runscript
    echo "This is what happens when you run the container..."


%post
    echo "Hello from inside the container"
    yum -y install vim-minimal
