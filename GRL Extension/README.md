# How to install

* Download the latest version of the <a href="https://www.eclipse.org/downloads/">Eclipse IDE for Java Developers</a>.
* Install the <a href="http://jucmnav.softwareengineering.ca/ucm/bin/view/ProjetSEG/DownloadingAndInstallation">jUCMNav extension</a>.
* Download the file `OCLRules.xml` from this directory.
* Import the OCR rules into the jUCMNav extension as follows: Go to `Preferences` (on Mac: `Eclipse > Preferences`, on Windows: `Window > Preferences`). Then, go to `jUCMNav > Static Semantics Checking`. Finally, click `import` and locate the XML file. The OCL rules are now imported into jUCMNav and are located in the group `Importaed`. In order to activate the OCL rules, check the box next to `Imported` to activate all imported OCL rules at once. Alternatively, click the box next to each individual OCL rule to activate it. Click `Apply` and then `Ok` to save the settings.
* 
# How to use the extension

* Create a GRL model in jUCMNav (<a href="http://jucmnav.softwareengineering.ca/ucm/bin/view/ProjetSEG/JUCMNavTutorials">jUCMNav tutorials</a>)
* Click on `jUCMNav > Verify Static Semantics`
* If a rule is violated, the `Problems` tab will show the error message. In order to view the `Problems` tab, click on `Window > Show View > Problems`.
