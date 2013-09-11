The 4 scripts you will need to grab to make Star-Made work with Multicraft are as follows (One is just the generated .cfg file)

You need to place this in your bin directory of multicraft. You then need to configure multicraft.conf to use prepare.sh.

https://raw.github.com/Standouthost/Multicraft/master/bin/prepare.sh

Edit Multicraft.conf and set the following variables.

userAgentDir = bin
userAgentFile = useragent
userAgentSuperuserPrepare = prepare.sh

Then place the other three files in your multicraft/jar directory

https://raw.github.com/Standouthost/Multicraft/master/jar/StarMade.cfg
https://raw.github.com/Standouthost/Multicraft/master/jar/StarMade.jar.conf
https://raw.github.com/Standouthost/Multicraft/master/jar/StarMade.sh

Make the StarMade.sh, and prepare.sh files executable with

chmod +x StarMade.sh
chmod +x prepare.sh


You will also need to place the latest version of StarMade-Starter.jar in your jar directory.