# googledorks
A couple of quick google dorks you can use, based off of a nullbyte article: https://null-byte.wonderhowto.com/how-to/find-passwords-exposed-log-files-with-google-dorks-0198557/

DISCLAIMER: Use all of these for legal purposes, I am in no way advising you to commit any crime and anything you do with this information is 100% your responsibility and is in no way connected to me.

All you need for these following commands is an internet connection and a google chrome browser, imput the following text into the search bar, fill in the YEAR requirement (if there is one), and press enter.

Also, for all of these examples you can use after:*YEAR* to find the results with the year. This can also be used in regular search. 

For *YEAR* put in the prior year, Ex.: if you wanted to find something from 2020 the year you would put in would be 2019


intitle:"index of" inurl:ftp after:*YEAR* //vulnerable files sent after specified year (ftp) 

intitle:"index of" inurl:http after:*YEAR* //vulnerable files sent after specified year (http)

filetype:env "DB_PASSWORD" after:*YEAR* //finds vulnerable configuration files with passwords

filetype:xls inurl:"emails.xls" //search for email lists

inurl:top.htm inurl:currenttime //find open cameras     

inurl:"lvappl.htm" //another way to find open cameras 

This scrapes the surface: I don't know much about google dorks: but here are some more from what I think is a credible source:

https://gbhackers.com/latest-google-dorks-list/

Feel free to fork this and add to it, if what you add works I can add it to the list.
