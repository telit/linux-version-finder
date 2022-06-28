# Linux Version Finder

Find the Linux versions where the commits passed as arguments are available.

When you start the tool the current directory must be a clone of the Linux stable repository:
git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git

E.g.:
git clone git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux.git
cd linux
~/linux-version-finder/linux-version-finder 22b106e5355d6e7a9c3b5cb5ed4ef22ae585ea94
v5.4.198 v5.10.121 v5.15.46 v5.17.14 v5.18.3 v5.19-rc1

or the check for multiple commits:
~/linux-version-finder/linux-version-finder 22b106e5355d6e7a9c3b5cb5ed4ef22ae585ea94 2939e1a86f758b55cdba73e29397dd3d94df13bc
v5.4.198 v5.10.121 v5.15.46 v5.17.14 v5.18.3 v5.19-rc1

## Help

linux-version-finder --help

## Linux Install requirements

    pip3 install -r requirements.txt
