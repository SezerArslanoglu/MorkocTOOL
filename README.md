# MorkocTOOL
MorkocTOOL is a tool BASED ON SGSI tool of @xiaoxindada for unpacking and repacking android firmware zip, system, vendor and product images.

                                           WHAT CAN THIS TOOL DO?
Unpacking Rom zips and turning them into sytem,vendor,product img. from system.new.dat.br, vendor.new.dat.br and product.new.dat.br
It can unpack System.img,vendor.img,product.img
It can repack editted system,vendor and product to System.img,vendor.img,product.img
It can turn .img files to system.new.dat.br again

                                          SUPPORTED ANDROID VERSIONS
12
11
10
9

                                             THIS TOOL REQUIRES:
Linux
SGSI TOOL of xiaoxindada

                                                HOW TO INSTALL
Firstly go https://github.com/xiaoxindada/SGSI-build-tool and download it on your linux based os.
in SGSI tool folder, open terminal and type
./setup.sh
./update.sh
Download my tool and extract it.

                                                  HOW TO USE

To Unpack a zip file and turn them into .img files: 
Copy the firmware/Rom zip file to tmp folder and open terminal on root folder of the tool and type
./full_ac.sh
It will ask for the name of the zip file. so type 
romfilename.zip
It will automatically extract new.dat.br or new.dat files and turn them into .img files.

To unpack an img file (system,vendor,product):
Just copy the img file to the tool's directory (if you unpacked zip file it will automatically move them to this directory) and type
./img_ac.sh partition name (without .img) Example: ./img_ac.sh system

Repacking the img file (sytem,vendor,product):
After you edited your img files just type
./img_kapat.sh


