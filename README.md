# Portest

Patch file automation for FreeBSD-ports.

With portest, you can create, update, patch and revert a port tree with svn,
git and portsnap. Portest can also do portlint testing, test a port with port
test, or poudriere, and also generate a list of ports a patchfile(s) will modify.

Portest is written in shell with minimal dependencies mostly using FreeBSD-base.
For full functionality, the following packages are requires,
* Git
* Portlint
* Poudriere
* Porttools (only Used if Poudriere is not)
* Tmux (for Poudriere parallel building)

This project was started as a need for patchfile automation requested on the mailing list.
https://lists.freebsd.org/pipermail/freebsd-ports/2015-November/101018.html
