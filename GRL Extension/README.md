# How to install Eclipse and jUCMNav
* Download the latest version of the <a href="https://www.eclipse.org/downloads/">Eclipse IDE for Java Developers</a>.
* Install the <a href="http://jucmnav.softwareengineering.ca/ucm/bin/view/ProjetSEG/DownloadingAndInstallation">jUCMNav extension</a>.

# How to import the OCL rules
* Download the file `OCLRules.xml` from this directory.
* Go to `Preferences` (on Mac: `Eclipse > Preferences`, on Windows: `Window > Preferences`). 
* Go to `jUCMNav > Static Semantics Checking`. 
* Click `import` and locate the XML file. The OCL rules are now imported into jUCMNav and are located in the group `Imported`. 
* In order to activate the OCL rules, check the box next to `Imported` to activate all imported OCL rules at once. Alternatively, click the box next to each individual OCL rule to activate it. 
* Finally, click `Apply` and then `Ok` to save the settings.

# How to import the GRL models

* Create a new jUCMNav project (<a href="http://jucmnav.softwareengineering.ca/ucm/bin/view/ProjetSEG/JUCMNavTutorials">jUCMNav tutorials</a>).
* Copy the file `eGovernmentEAPrinciples.jucm' into your project source folder.
* Refresh the project.
