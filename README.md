<img src="https://i.imgur.com/0GnrwaU.png">

Initializing Repository
-----------------------

Repo initialization :
    
    repo init -u https://github.com/BlissRoms-miatoll/platform_manifest.git -b q --depth=1

sync repo :

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
    

Building
--------
    . build/envsetup.sh
    blissify device-codename
    
