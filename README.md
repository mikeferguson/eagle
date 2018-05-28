## Eagle CAD Stuff

This is a collection of libraries and board designs using Eagle CAD.

## Installing Eagle 7.1 (on Ubuntu 18.04)

    sudo apt-get install gcc-multilib
    sudo apt-get install libxrender1:i386 libxrandr2:i386 libxcursor1:i386 libfreetype6:i386 libfontconfig1:i386 libxi6:i386 libstdc++6:i386 libjpeg62:i386 libssl1.0.0:i386

    wget http://web.cadsoft.de/ftp/eagle/program/7.1/eagle-lin-7.1.0.run
    chmod a+x eagle-lin-7.1.0.run
    ./eagle-lin-7.1.0.run /opt

## Adding Launcher on Ubuntu 18.04
Add a file called eagle.desktop to ~/.local/share/applications:

    #!/usr/bin/env xdg-open
    [Desktop Entry]
    Comment[en_US]=Eagle 7.1
    Terminal=false
    Name[en_US]=Eagle
    Exec=/opt/eagle-7.1.0/bin/eagle
    Type=Application
    Icon=/opt/eagle-7.1.0/bin/eagleicon50.png
    StartupWMClass=dont_care
