#Fireworks Export Moddifcation for coolblueweb

This is a modification of the fireworks default <em>DEFAULT DREAMWEAVER</em> export for Fireworks.

<sub><sup<em>*Always make a backup of the original file before using this one, as it might break the export for fireworks for you.</em></sup></sub>

##Where to put it...

be sure replace the <strong>SLICES.XTT</strong> in the dreamweaver folder which you can find here:

	/Applications/Adobe\ Fireworks\ CS6/Configuration/HTML\ Code/Dreamweaver

<sub><sup>You can probably use it in the other export types but to be safe this is where it is working for me.</sup></sub>

After you've replaced the slices.xtt file with this one or made the original a backup you should do these checks to make sure that you are exporting for the default set up.

###Step one:

Check your export default settings to be configured to the figure below:

![step one](https://dl.dropbox.com/u/52662569/exp-01.png "Step One")

###Step Two:

Check and make sure your Option Settings are as follows:

#####General Tab

Make sure that the HTML setting is set to Dreamweaver HTML (if you put it in a different export folder use that one instead).

Change the extension to .php save yourself some time since you'll need them as php files for the global nav include to work.

And don't forget to change page alignment to center.
![step two](https://dl.dropbox.com/u/52662569/exp-02.png "Step Two")

#####Table Tab

This is where we want to make sure that the tables are nested and have no borders otherwise it could look really messed up and floods the html with unnecessary spacers it generates

![step three]("Step Three")
