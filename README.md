local_manifests
===============
[TEMPLATE] local_manifest.xml

This is a simple drop-in template I put together to save time and so I can be lazy.


To be used in:

    $ ls ~/android/.repo/local_manifests/

Myself I create a hidden local_manifests directory then alias the xml file I want to use.

    $ git clone git://github.com/pax10/local_manifests.git -b alm ~/android/.local_manifests
    
    $ mkdir -p ~/android/.repo/local_manifests
    
    $ ln -s /home/`whoami`/android/.local_manifests/local_manifest_rz.xml /home/`whoami`/android/.repo/local_manifests/local_manifest.xml

Then I just run repo sync and wait.

Branches:

  master: local_manifest.xml template.
  
  alm: all the manifest I've put together while playing with various rom source.

Master Branch: template base
