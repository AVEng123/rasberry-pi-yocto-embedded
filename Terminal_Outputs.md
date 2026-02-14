shubham@shubham-VirtualBox:~$ ls

Desktop  Documents  Downloads  go  Music  Pictures  Public  Shubham\_Ubuntu\_AI\_Agent  snap  Templates  Videos

shubham@shubham-VirtualBox:~$ cd Documents/

shubham@shubham-VirtualBox:~/Documents$ ls

CPU  yocto

shubham@shubham-VirtualBox:~/Documents$ 

shubham@shubham-VirtualBox:~/Documents$ 

shubham@shubham-VirtualBox:~/Documents$ 

shubham@shubham-VirtualBox:~/Documents$ sudo apt update

\[sudo] password for shubham: 

Get:1 http://security.ubuntu.com/ubuntu noble-security InRelease \[126 kB]   

Hit:2 http://in.archive.ubuntu.com/ubuntu noble InRelease                   

Get:3 http://in.archive.ubuntu.com/ubuntu noble-updates InRelease \[126 kB]

Get:4 http://security.ubuntu.com/ubuntu noble-security/main amd64 Packages \[1,448 kB]

Get:5 http://in.archive.ubuntu.com/ubuntu noble-backports InRelease \[126 kB]

Get:6 http://in.archive.ubuntu.com/ubuntu noble-updates/main amd64 Packages \[1,742 kB]

Get:7 http://security.ubuntu.com/ubuntu noble-security/main Translation-en \[234 kB]

Get:8 http://security.ubuntu.com/ubuntu noble-security/main amd64 Components \[21.5 kB]

Get:9 http://security.ubuntu.com/ubuntu noble-security/main amd64 c-n-f Metadata \[9,892 B]                

Get:10 http://security.ubuntu.com/ubuntu noble-security/restricted amd64 Packages \[2,452 kB]

Get:11 http://security.ubuntu.com/ubuntu noble-security/restricted Translation-en \[564 kB]           

Get:12 http://security.ubuntu.com/ubuntu noble-security/restricted amd64 Components \[212 B]        

Get:13 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Packages \[930 kB]

Get:14 http://security.ubuntu.com/ubuntu noble-security/universe Translation-en \[212 kB]    

Get:15 http://security.ubuntu.com/ubuntu noble-security/universe amd64 Components \[74.3 kB]        

Get:16 http://security.ubuntu.com/ubuntu noble-security/universe amd64 c-n-f Metadata \[19.9 kB]       

Get:17 http://security.ubuntu.com/ubuntu noble-security/multiverse amd64 Components \[212 B]          

Get:18 http://in.archive.ubuntu.com/ubuntu noble-updates/main amd64 Components \[175 kB]            

Get:19 http://in.archive.ubuntu.com/ubuntu noble-updates/main amd64 c-n-f Metadata \[16.5 kB]

Get:20 http://in.archive.ubuntu.com/ubuntu noble-updates/restricted amd64 Components \[212 B]

Get:21 http://in.archive.ubuntu.com/ubuntu noble-updates/universe amd64 Packages \[1,529 kB]

Get:22 http://in.archive.ubuntu.com/ubuntu noble-updates/universe Translation-en \[313 kB]

Get:23 http://in.archive.ubuntu.com/ubuntu noble-updates/universe amd64 Components \[386 kB]

Get:24 http://in.archive.ubuntu.com/ubuntu noble-updates/universe amd64 c-n-f Metadata \[31.9 kB]

Get:25 http://in.archive.ubuntu.com/ubuntu noble-updates/multiverse amd64 Components \[940 B]

Get:26 http://in.archive.ubuntu.com/ubuntu noble-backports/main amd64 Components \[7,284 B]

Get:27 http://in.archive.ubuntu.com/ubuntu noble-backports/restricted amd64 Components \[216 B]

Get:28 http://in.archive.ubuntu.com/ubuntu noble-backports/universe amd64 Components \[10.5 kB]

Get:29 http://in.archive.ubuntu.com/ubuntu noble-backports/multiverse amd64 Components \[212 B]

Fetched 10.6 MB in 5s (2,235 kB/s)               

Reading package lists... Done

Building dependency tree... Done

Reading state information... Done

264 packages can be upgraded. Run 'apt list --upgradable' to see them.

shubham@shubham-VirtualBox:~/Documents$ sudo apt-get install build-essential chrpath cpio debianutils diffstat file gawk gcc git iputils-ping libacl1 locales python3 python3-git python3-jinja2 python3-pexpect python3-pip python3-subunit socat texinfo unzip wget xz-utils zstd

Reading package lists... Done

Building dependency tree... Done

Reading state information... Done

build-essential is already the newest version (12.10ubuntu1).

cpio is already the newest version (2.15+dfsg-1ubuntu2).

cpio set to manually installed.

debianutils is already the newest version (5.17build1).

debianutils set to manually installed.

file is already the newest version (1:5.45-3build1).

file set to manually installed.

gcc is already the newest version (4:13.2.0-7ubuntu1).

git is already the newest version (1:2.43.0-1ubuntu7.3).

iputils-ping is already the newest version (3:20240117-1ubuntu0.1).

iputils-ping set to manually installed.

locales is already the newest version (2.39-0ubuntu8.7).

locales set to manually installed.

python3 is already the newest version (3.12.3-0ubuntu2.1).

python3-jinja2 is already the newest version (3.1.2-1ubuntu1.3).

python3-jinja2 set to manually installed.

python3-pexpect is already the newest version (4.9-2).

python3-pexpect set to manually installed.

python3-pip is already the newest version (24.0+dfsg-1ubuntu1.3).

unzip is already the newest version (6.0-28ubuntu4.1).

unzip set to manually installed.

wget is already the newest version (1.21.4-1ubuntu4.1).

wget set to manually installed.

xz-utils is already the newest version (5.6.1+really5.4.5-1ubuntu0.2).

xz-utils set to manually installed.

zstd is already the newest version (1.5.5+dfsg2-2build1.1).

zstd set to manually installed.

The following packages were automatically installed and are no longer required:

&nbsp; libgl1-amber-dri libglapi-mesa

Use 'sudo apt autoremove' to remove them.

Suggested packages:

&nbsp; gawk-doc libxml-sax-expatxs-perl python-git-doc python-testtools-doc debhelper texlive-base texlive-latex-base texlive-plain-generic texlive-fonts-recommended

The following NEW packages will be installed:

&nbsp; chrpath diffstat gawk libsigsegv2 libtext-unidecode-perl libxml-libxml-perl libxml-namespacesupport-perl libxml-sax-base-perl libxml-sax-expat-perl libxml-sax-perl python3-extras python3-fixtures

&nbsp; python3-git python3-gitdb python3-pbr python3-smmap python3-subunit python3-testtools socat tex-common texinfo texinfo-lib

The following packages will be upgraded:

&nbsp; acl libacl1

2 upgraded, 22 newly installed, 0 to remove and 262 not upgraded.

Need to get 3,398 kB of archives.

After this operation, 17.1 MB of additional disk space will be used.

Get:1 http://in.archive.ubuntu.com/ubuntu noble/main amd64 libsigsegv2 amd64 2.14-1ubuntu2 \[15.0 kB]

Get:2 http://in.archive.ubuntu.com/ubuntu noble/main amd64 gawk amd64 1:5.2.1-2build3 \[463 kB]

Get:3 http://in.archive.ubuntu.com/ubuntu noble-updates/main amd64 acl amd64 2.3.2-1build1.1 \[39.4 kB]

Get:4 http://in.archive.ubuntu.com/ubuntu noble-updates/main amd64 libacl1 amd64 2.3.2-1build1.1 \[16.8 kB]

Get:5 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 chrpath amd64 0.16-2build1 \[12.8 kB]

Get:6 http://in.archive.ubuntu.com/ubuntu noble/main amd64 diffstat amd64 1.66-1build1 \[29.7 kB]

Get:7 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 libtext-unidecode-perl all 1.30-3 \[105 kB]

Get:8 http://in.archive.ubuntu.com/ubuntu noble/main amd64 libxml-namespacesupport-perl all 1.12-2 \[13.5 kB]

Get:9 http://in.archive.ubuntu.com/ubuntu noble/main amd64 libxml-sax-base-perl all 1.09-3 \[18.9 kB]

Get:10 http://in.archive.ubuntu.com/ubuntu noble/main amd64 libxml-sax-perl all 1.02+dfsg-3 \[57.0 kB]

Get:11 http://in.archive.ubuntu.com/ubuntu noble/main amd64 libxml-libxml-perl amd64 2.0207+dfsg+really+2.0134-1build4 \[304 kB]

Get:12 http://in.archive.ubuntu.com/ubuntu noble/main amd64 libxml-sax-expat-perl all 0.51-2 \[8,644 B]

Get:13 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 python3-extras all 1.0.0-5 \[7,066 B]

Get:14 http://in.archive.ubuntu.com/ubuntu noble/main amd64 python3-pbr all 5.11.1-0ubuntu1 \[66.5 kB]

Get:15 http://in.archive.ubuntu.com/ubuntu noble/main amd64 python3-testtools all 2.7.1-3 \[123 kB]

Get:16 http://in.archive.ubuntu.com/ubuntu noble/main amd64 python3-fixtures all 4.0.1-3 \[33.6 kB]

Get:17 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 python3-smmap all 6.0.0-1 \[20.5 kB]

Get:18 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 python3-gitdb all 4.0.11-1 \[46.2 kB]

Get:19 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 python3-git all 3.1.37-3 \[138 kB]

Get:20 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 python3-subunit all 1.4.2-3build1 \[67.6 kB]

Get:21 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 tex-common all 6.18 \[32.8 kB]

Get:22 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 texinfo-lib amd64 7.1-3build2 \[133 kB]

Get:23 http://in.archive.ubuntu.com/ubuntu noble/universe amd64 texinfo all 7.1-3build2 \[1,273 kB]

Get:24 http://in.archive.ubuntu.com/ubuntu noble/main amd64 socat amd64 1.8.0.0-4build3 \[374 kB]

Fetched 3,398 kB in 3s (976 kB/s)

Selecting previously unselected package libsigsegv2:amd64.

(Reading database ... 213429 files and directories currently installed.)

Preparing to unpack .../libsigsegv2\_2.14-1ubuntu2\_amd64.deb ...

Unpacking libsigsegv2:amd64 (2.14-1ubuntu2) ...

Setting up libsigsegv2:amd64 (2.14-1ubuntu2) ...

Selecting previously unselected package gawk.

(Reading database ... 213436 files and directories currently installed.)

Preparing to unpack .../gawk\_1%3a5.2.1-2build3\_amd64.deb ...

Unpacking gawk (1:5.2.1-2build3) ...

Preparing to unpack .../acl\_2.3.2-1build1.1\_amd64.deb ...

Unpacking acl (2.3.2-1build1.1) over (2.3.2-1build1) ...

Preparing to unpack .../libacl1\_2.3.2-1build1.1\_amd64.deb ...

Unpacking libacl1:amd64 (2.3.2-1build1.1) over (2.3.2-1build1) ...

Setting up libacl1:amd64 (2.3.2-1build1.1) ...

Selecting previously unselected package chrpath.

(Reading database ... 213602 files and directories currently installed.)

Preparing to unpack .../00-chrpath\_0.16-2build1\_amd64.deb ...

Unpacking chrpath (0.16-2build1) ...

Selecting previously unselected package diffstat.

Preparing to unpack .../01-diffstat\_1.66-1build1\_amd64.deb ...

Unpacking diffstat (1.66-1build1) ...

Selecting previously unselected package libtext-unidecode-perl.

Preparing to unpack .../02-libtext-unidecode-perl\_1.30-3\_all.deb ...

Unpacking libtext-unidecode-perl (1.30-3) ...

Selecting previously unselected package libxml-namespacesupport-perl.

Preparing to unpack .../03-libxml-namespacesupport-perl\_1.12-2\_all.deb ...

Unpacking libxml-namespacesupport-perl (1.12-2) ...

Selecting previously unselected package libxml-sax-base-perl.

Preparing to unpack .../04-libxml-sax-base-perl\_1.09-3\_all.deb ...

Unpacking libxml-sax-base-perl (1.09-3) ...

Selecting previously unselected package libxml-sax-perl.

Preparing to unpack .../05-libxml-sax-perl\_1.02+dfsg-3\_all.deb ...

Unpacking libxml-sax-perl (1.02+dfsg-3) ...

Selecting previously unselected package libxml-libxml-perl.

Preparing to unpack .../06-libxml-libxml-perl\_2.0207+dfsg+really+2.0134-1build4\_amd64.deb ...

Unpacking libxml-libxml-perl (2.0207+dfsg+really+2.0134-1build4) ...

Selecting previously unselected package libxml-sax-expat-perl.

Preparing to unpack .../07-libxml-sax-expat-perl\_0.51-2\_all.deb ...

Unpacking libxml-sax-expat-perl (0.51-2) ...

Selecting previously unselected package python3-extras.

Preparing to unpack .../08-python3-extras\_1.0.0-5\_all.deb ...

Unpacking python3-extras (1.0.0-5) ...

Selecting previously unselected package python3-pbr.

Preparing to unpack .../09-python3-pbr\_5.11.1-0ubuntu1\_all.deb ...

Unpacking python3-pbr (5.11.1-0ubuntu1) ...

Selecting previously unselected package python3-testtools.

Preparing to unpack .../10-python3-testtools\_2.7.1-3\_all.deb ...

Unpacking python3-testtools (2.7.1-3) ...

Selecting previously unselected package python3-fixtures.

Preparing to unpack .../11-python3-fixtures\_4.0.1-3\_all.deb ...

Unpacking python3-fixtures (4.0.1-3) ...

Selecting previously unselected package python3-smmap.

Preparing to unpack .../12-python3-smmap\_6.0.0-1\_all.deb ...

Unpacking python3-smmap (6.0.0-1) ...

Selecting previously unselected package python3-gitdb.

Preparing to unpack .../13-python3-gitdb\_4.0.11-1\_all.deb ...

Unpacking python3-gitdb (4.0.11-1) ...

Selecting previously unselected package python3-git.

Preparing to unpack .../14-python3-git\_3.1.37-3\_all.deb ...

Unpacking python3-git (3.1.37-3) ...

Selecting previously unselected package python3-subunit.

Preparing to unpack .../15-python3-subunit\_1.4.2-3build1\_all.deb ...

Unpacking python3-subunit (1.4.2-3build1) ...

Selecting previously unselected package tex-common.

Preparing to unpack .../16-tex-common\_6.18\_all.deb ...

Unpacking tex-common (6.18) ...

Selecting previously unselected package texinfo-lib.

Preparing to unpack .../17-texinfo-lib\_7.1-3build2\_amd64.deb ...

Unpacking texinfo-lib (7.1-3build2) ...

Selecting previously unselected package texinfo.

Preparing to unpack .../18-texinfo\_7.1-3build2\_all.deb ...

Unpacking texinfo (7.1-3build2) ...

Selecting previously unselected package socat.

Preparing to unpack .../19-socat\_1.8.0.0-4build3\_amd64.deb ...

Unpacking socat (1.8.0.0-4build3) ...

Setting up gawk (1:5.2.1-2build3) ...

Setting up python3-pbr (5.11.1-0ubuntu1) ...

Setting up python3-extras (1.0.0-5) ...

Setting up libxml-namespacesupport-perl (1.12-2) ...

Setting up texinfo-lib (7.1-3build2) ...

Setting up acl (2.3.2-1build1.1) ...

Setting up tex-common (6.18) ...

update-language: texlive-base not installed and configured, doing nothing!

Setting up libxml-sax-base-perl (1.09-3) ...

Setting up socat (1.8.0.0-4build3) ...

Setting up diffstat (1.66-1build1) ...

Setting up libtext-unidecode-perl (1.30-3) ...

Setting up python3-smmap (6.0.0-1) ...

Setting up chrpath (0.16-2build1) ...

Setting up python3-gitdb (4.0.11-1) ...

Setting up libxml-sax-perl (1.02+dfsg-3) ...

update-perl-sax-parsers: Registering Perl SAX parser XML::SAX::PurePerl with priority 10...

update-perl-sax-parsers: Updating overall Perl SAX parser modules info file...



Creating config file /etc/perl/XML/SAX/ParserDetails.ini with new version

Setting up python3-git (3.1.37-3) ...

Setting up libxml-libxml-perl (2.0207+dfsg+really+2.0134-1build4) ...

update-perl-sax-parsers: Registering Perl SAX parser XML::LibXML::SAX::Parser with priority 50...

update-perl-sax-parsers: Registering Perl SAX parser XML::LibXML::SAX with priority 50...

update-perl-sax-parsers: Updating overall Perl SAX parser modules info file...

Replacing config file /etc/perl/XML/SAX/ParserDetails.ini with new version

Setting up libxml-sax-expat-perl (0.51-2) ...

update-perl-sax-parsers: Registering Perl SAX parser XML::SAX::Expat with priority 50...

update-perl-sax-parsers: Updating overall Perl SAX parser modules info file...

Replacing config file /etc/perl/XML/SAX/ParserDetails.ini with new version

Setting up texinfo (7.1-3build2) ...

Setting up python3-testtools (2.7.1-3) ...

Setting up python3-subunit (1.4.2-3build1) ...

Setting up python3-fixtures (4.0.1-3) ...

Processing triggers for install-info (7.1-3build2) ...

Processing triggers for libc-bin (2.39-0ubuntu8.7) ...

Processing triggers for man-db (2.12.0-4build2) ...

shubham@shubham-VirtualBox:~/Documents$ 

shubham@shubham-VirtualBox:~/Documents$ 

shubham@shubham-VirtualBox:~/Documents$ 

shubham@shubham-VirtualBox:~/Documents$ 

shubham@shubham-VirtualBox:~/Documents$ ls

CPU  yocto

shubham@shubham-VirtualBox:~/Documents$ cd yocto/

shubham@shubham-VirtualBox:~/Documents/yocto$ ls

shubham@shubham-VirtualBox:~/Documents/yocto$ git clone -b scarthgap https://git.yoctoproject.org/poky poky-rpi

Cloning into 'poky-rpi'...

remote: Enumerating objects: 710535, done.

remote: Counting objects: 100% (900/900), done.

remote: Compressing objects: 100% (527/527), done.

remote: Total 710535 (delta 576), reused 516 (delta 372), pack-reused 709635 (from 1)

Receiving objects: 100% (710535/710535), 222.41 MiB | 1.50 MiB/s, done.

Resolving deltas: 100% (517147/517147), done.

shubham@shubham-VirtualBox:~/Documents/yocto$ 



££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££



shubham@shubham-VirtualBox:~/Documents/yocto/poky-rpi$ git clone -b scarthgap https://github.com/agherzan/meta-raspberrypi.git
Cloning into 'meta-raspberrypi'...
remote: Enumerating objects: 12201, done.
remote: Counting objects: 100% (184/184), done.
remote: Compressing objects: 100% (101/101), done.
remote: Total 12201 (delta 106), reused 87 (delta 83), pack-reused 12017 (from 2)
Receiving objects: 100% (12201/12201), 4.23 MiB | 3.67 MiB/s, done.
Resolving deltas: 100% (6515/6515), done.
shubham@shubham-VirtualBox:~/Documents/yocto/poky-rpi$



££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££££

shubham@shubham-VirtualBox:~/Documents/yocto$ git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint: 
hint:   git config --global init.defaultBranch <name>
hint: 
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint: 
hint:   git branch -m <name>
Initialized empty Git repository in /home/shubham/Documents/yocto/.git/
shubham@shubham-VirtualBox:~/Documents/yocto$ git remote add origin https://github.com/AVEng123/rasberry-pi-yocto-embedded.git
shubham@shubham-VirtualBox:~/Documents/yocto$ git pull origin main --allow-unrelated-histories
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (5/5), 1.83 KiB | 1.83 MiB/s, done.
From https://github.com/AVEng123/rasberry-pi-yocto-embedded
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
shubham@shubham-VirtualBox:~/Documents/yocto$ 


