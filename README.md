# hello-world
All new dogs where once pups. and I is confused, so it all started with a new toy, and not alot of reseach. Then followed by a bit of this a bit of that .A video or 2, a 1st attemp ,a good idea a bad idea a fail, a mega fail, a little progress , a 16 bit sample proplem, i dont know what or how to fix that ,and a try this gui quick , pray it knocks an hour off terminal build time. 
Ok so I am just trying to follow the guide at this address https://guides.github.com/activities/hello-world/ I am lost, but just made another branch. I have master and readme-edits, I clicked onn README-md then the pencil top right ,then wrote this ... A little about me before clicking the commit. rather be following the terminal way. ok i got a sdr from amazon, just started using linux and have no other working device, when i got the package and email I discovered there guide to instailing just covered the mac and windows, i emailed them asking for a hint in the right direction and they helped out,  Essentially, you need to checkout the code with:
 

   |. git clone git://git.osmocom.org/rtl-sdr.git

 
...and then build with cmake or autotools or a similar software meant for compiling, like the following instruction set:
 

    cd rtl-sdr/
    mkdir build
    cd build
    cmake ../
    make
    sudo make install
    sudo ldconfig

 
For some distros you may need to blacklist the DVB driver in /etc/modprobe.d/blacklist.conf with:
 

    blacklist dvb_usb_rtl28xxu
   }
   i also watched a video on hak5 youtube, and I partly read all instruction's. started buiding using cmake, getting git clone etc.etc while all the time none the commands to list the device actually ever showed it as listing anything there, no led, so i have sdrangelove in my home folder, a rtl-sdr, a project1 and no account with github, thats why im here at this step, just going to commit gui helppage now.
   
