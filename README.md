# Kmean
Sample of PAL using KMEANS


This is a project that uses the kmeans algorithm to group like data  and display it in the browser.  The output is built using 
calculation views to gather the data to be processed and XSJS code to do the processing.  You will find all the project code in 
PALKmeans directory.  

PALKmeans\calculationview
	SAP_CA_NETSALES: gather the netsales
PALKmeans\html
	The html file that you call in the browser
PALKmeans\xsjs
	The XSJS code that does the heavy lifting
PALKmeans\xsaccess
This is the .xsaccess file that all XSJS apps require but since it came from Windows, it was renamed to __emptyName__.  When used it needs 
to be renamed to .xsaccess.

PALKmeans\xsapp
This is the .xsaccess file that all XSJS apps require but since it came from Windows, it was renamed to __emptyName__.  When used it needs 
to be renamed to .xsapp.


These directories come from the REPO_20160204-174527791-NDB---KMEANS_PAL_DU.tgz delivery unit.  This file can be used to import the code to
your HANA system.  The repository shows the structure of the app but best to import the delivery unit and work from there.  The calculation 
view uses SBODEMOGB.

