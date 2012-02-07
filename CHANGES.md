## Version 1.2.7 - 7 Feb 2012

### Web Application

**FEATURES**

* Tab for Project level statistics to the genome page
* Total number of samples displayed in the project list view
* Cancel Edit link to return to main view without saving
* More descriptive page titles
* Pagination added to tables
* Default Mapped tab changed to Alignment

**FIXES**

* Remove broken Add Sample button on Sample list page
* Broken Edit Alignment button
* Genomes features not displaying even when features existed
* Formatting for Add User popup

## Version 1.2.6 - 6 Feb 2012

### Web Application

**FIXES**

* Mapped alignemnt positions line up properly with genome positions
* Open new tab when clicking on read in JBrowse
* Adds link to show all samples from genome details page
* Edit User button properly labelled and working
* Added cancer type to sample page
* Users and UserRoles save properly

### Pipeline

**FIXES**

* Subtraction filters unmapped reads before building mapped alignments

## Version 1.2.5 - 3 Feb 2012

### Web Application

**FIXES**

* Show reads that map to both reference sets in red

## Version 1.2.4 - 2 Feb 2012*

### Web Application

**FIXES**

* Updated README.md
* Corrected JavaScript issues which broke adding users

## Version 1.2.3 - 30 Jan 2012

### Web Application

**FIXES**

* Corrected Config Access issues

## Version 1.2.2 - 25 Jan 2012

### Web Application

**FEATURES** 

* Config file location can be specified through Java System Property

**FIXES**

* Deploying under Tomcat or Jetty works again
* OpenJDK compatible (no longer requires Oracle VM)
* 404 issue for reads that didn't map to any gene

## Version 1.2.1 - 23 Jan 2012

### Web Application

**FIXES**

* Error on JBrowse page

## Version 1.2 - 20 Jan 2012

### Web Application

**FEATURES**

* Simplified installation
* Added embedded Jetty server
* Mapped read details page
* Display read alignment against genome sequence

**FIXES**

* UserRoles not being deleted with User
* Edit button works in FF 3.6
* Statistics tables sorted by max coverage

### Pipeline

**FEATURES**

* Utility to create FastQ files from unmapped reads
* Utility to return intersection of FastQ files
* Utility to return filter FastQ files
* Added mapq threshold flag to subtraction
* Gbloader can now load bacteria and fungal genomes
* Saves genome sequences to database using GridFS

**FIXES**

* Reduced memory footprint when calculating statistics 
* use subprocesses instead of os.system
* mapq scores filter needs to include 0 <= mapq <=3 due to multiple mapping reads

## Version 1.1 - 25 Nov 2011

### Web Application

**FEATURES**  

* New Admin Interface
* Role have access levels for more control over user access
* LDAP option when creating a new user to stop credentials from being sent to keep login control with the LDAP server
* Project owners can control the visibility of their project and user access levels
* Create Alignments from Project page
* Project/Samples/Alignemnts and Users can all be edited and delete
* Reads that map to both pathogen and reference genomes are highlighted

**FIXES**  

* Popups populated through ajax calls
* Grids refreshed rather than forcing page reload
* Moved Admin link to nav bar

### Pipeline

**FEATURES**  

* Adds support for pair-end reads

## 28 Oct 2011
### Web Application - v1.0.2
#### Fixes
* Fixes JBrowse caching old tracks

## 20 Oct 2011
### Web Application - v1.0.1
#### Fixes
* Projects seen in JBrowse filtered by access privileges

## 19 Oct 2011
### Pipeline - v1.0.1
#### Fixes
* Added support for MongoDB authentication

## 19 Oct 2011
### Pipeline - v1.0
* Initial Release

### Pipeline - v1.0
* Initial Release