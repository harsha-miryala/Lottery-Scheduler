This is a implementation of lottery scheduler for MINIX 3.1.7.
How To Install:
1. Copy sched.patch to /usr directoy in your MINIX system.
2. Run "patch -p1 < sched.patch" in /usr directory.
3. Run "make install" in /usr/src/tools directory.
4. Reboot your MINIX and enter the new customize kernel.
Note:
Please do this in a clean src directories on MINIX 3.1.7. I make no guaratee
this patch would work with other patches, or other MINIX versions.
Check sched.design if you want further information on this patch.
