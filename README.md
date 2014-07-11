PDF-Inspector
=============
It is a fork from PDF-Inspector of Docear project. 

Installation
=============

Build
===========
mvn package 
   
./run.sh to see the options similar to the followings

usage: java -jar DocearPdfInspector [OPTION]... [FILE]...
            Inspect and extract information of PDF file(s) and return them
            as a CSV file or on the command line. Files may contain
            wildcards.
            Selected fields are returned in the following order (if
            included): name, hash, title, text, time
 -delimiter <arg>   use a specific delimiter String, using "|" by default
 -duration          include duration needed for extracting the data set
 -hash              generate a unique hash for the PDF file that does not
                    change even when creating annotations in the PDF
 -header            include header into the data set
 -help              print help and exit
 -name              include the file name
 -out <arg>         write to a file
 -outappend         append to file, instead of overwriting it
 -text              extract plain text of the PDF file
 -title             extract the title of the PDF file

