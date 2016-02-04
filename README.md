# Responsive-Table-Version-1.0
This is a Jquery plugin that converts any html tables in a site to a responsive generated version, In mobile view it changes to an 
accordion that slides open and closes for each table.

|=====================| RESPONSIVE TABLE! |=====================|

The responsiveTable plugin is a plugin that creates a 100% dynamic and responsive
version of any tables with in the html of a site. It applies id's and classes
enabling easy styling, it only has two parameters:

	01. tableNames - Tables names allow each table to have it's own name
	    using an array that is passed in.

	02. customMedia - Custom Media takes either a true or a false which
	    enables to use either default media qeuries or custom qeuries.

EXAMPLE:

$("body").myAlert(tableNames, true);

The selector at the beginning doasn't matter, as the tables will 
replace the position of the html tables.

PARAMETERS:

tableNames, customMedia
