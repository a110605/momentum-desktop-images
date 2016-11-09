#Momentum for Mac desktop
This is a simple python script that will download the Momentum daily images to a folder on your computer, allowing you to point your desktop backgrounds to it.

#Configuration
First you nee to get your Momentum Client ID

1. Open a new browser tab to get Momentum loaded up.
2. Click on the settings cog bottom left
3. Click on About
4. Double click on the version number under the momentum logo
5. Copy the ID that is then shown
6. Open the `config.py` file
7. replace `CLIENT_ID` with the copied id

#Manual Run
Once you have set you `CLIENT_ID` you can run the script to get the current images.

    $ python ./sync_momentum.py

#Automatically Run
On OSX, you can set up the python script to run once a day, automatically downloading the images.

Run the following shell command form this directory to create the launch agent that will run once a day

    $ ./install.sh

To remove the launch agent, run the uninstall script

    $ ./uninstall.sh

#Desktops
You can then point your desktop folder to the `pictures` folder that is created to get all the goodness of momentum on your desktop.

#Licence and Support
NO WARRANTY. THE SOFTWARE IS PROVIDED TO YOU "AS IS" AND "WITH ALL FAULTS."  
ANY USE OF THE SOFTWARE IS ENTIRELY AT YOUR OWN RISK.