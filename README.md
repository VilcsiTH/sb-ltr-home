___sb-ltr-home___

A version of the PHP Loot Table Randomizer that can be run at home, in case the original site ( https://fasguy.ga/sb_ltr_external/ ) goes down.

Noob-friendly tutorial included below.

___Installation___
1. Download the master branch zip file using github's green "Download or Clone" button. Extract it somewhere.

2. Download and install XAMPP from https://www.apachefriends.org/index.html . (You can uncheck all the boxes during installation to minimize the install. Make sure to launch the control panel, it asks at the end of the installation.)

3. In the control panel, find a button that says "Explorer" with a yellow folder icon. It will open up your XAMPP folder.(Don't close XAMPP yet.)

4. Go into the "htdocs" folder, and drag and drop the CONTENTS of sb-ltr-home-master into that folder.(So that you have 3 files inside htdocs ending in .php: index, download and loot_table_randomizer.)

5. Go back to the XAMPP control panel and next to Apache, click the Start button. Once it's done, you should be able to click the Admin button, and the page will open in your browser.

6. Generate your Loot Table Randomizer and play!

ALTERNATIVELY you could edit the index.php already inside the htdocs folder. Simply swap the

header('Location: '.$uri.'/dashboard/');

line to

header('Location: '.$uri.'/sb-ltr-home-master/');

and afterwards, put the sb-ltr-home-master FOLDER inside htdocs.(NOT the files or the zip, but the folder itself.)

___Credits___

Original Code by Fasguy (https://github.com/Fasguy/sb-ltr)

All the guys from the original credits:

Original Loot table randomizer created by SethBling (https://www.youtube.com/channel/UC8aG3LDTDwNR1UQhSn9uVrw)

Using a modified version of Vincent's PclZip (http://phpconcept.net/pclzip/)

Using South-Paw's Minecraft webfont (https://github.com/South-Paw/Minecraft-Webfont-and-Colors)

hungryhyena78 for feedback on usage (https://www.twitch.tv/hungryhyena78)
