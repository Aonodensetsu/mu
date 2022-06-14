# Game plan
This file lists the steps taken to create my minimal Linux distro, plans, requirements and all things that I wish to accomplish.
- [ ] Complete the BLFS tutorial  
BLFS is an extension to LFS and discusses more advances features of a Linux distro, this step will be taken at the same time as further work
is being done with designing the features I wish to include.
- [ ] Complete the multilib LFS tutorial  
By default, LFS does not support running 32-bit (or lower) apps on a 64-bit system, and some apps might not have 64-bit versions. I will
follow the multilib version of LFS to check how to enable support for lower-bit software on my distro.
# Main features
The things listed below are features my distro cannot go without.
- [ ] as small as possible
- [ ] apt support
- [ ] 64-bit multilib
# Requirements
This is the section that goes into more detail about how each feature required is going to get accomplished.
### as small as possible
I want to make sure the footprint of the distro is as small as possible, while including several features I am familiar with from other distros
### apt support
apt has several dependencies, therefore I will need to build them and make sure they work correctly to use apt as my package manager of
choice
### 64-bit multilib
I want to make sure lower-bit software is able to be used in my distro for compatibility reasons. I will make sure to include multilib for this purpose.
# Packages I want
apt, bash, dhcpcd, systemd, wget
