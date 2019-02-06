# Splunk
  * Splunk is the log collection and analysis tool.
#### Splunk facilitates:
  * Real-time log forwarding
  * Real-time syslog analysis
  * Real-time server monitoring
  * Real-time alerts/notification
  * Historical data/log store and analysis
#### Install inside amazon linux machine
  * https://www.splunk.com/en_us/download/splunk-enterprise/thank-you-enterprise.html 
  * click on above link and copy the link of download via command line 
  * tar -xvzf file   -- to untar the file
#### cd splunk/bin and run ./splunk start
  * give username and password (my username is ec2-user)
  * remember the username and password and login using same username and password to pubic-ip:8000
  * Congratulation, you are welcome to use it.
#### Inside Splunk
  * On left top side, you can see Search and Reporting. When you click it, you will see
    * Search Bar -> for entering our searches
    * A time range picker for the search 
    * Links to the search documentation and tutorial
    * Information on data splunk is indexed
    * Menu to view and re-run past searches
#### Note: In search bar; you can run 
  * Comparison operators like:=  !=  <   <=   >
  * if you search by---- status=50* ; it will return every status error code like 503, 505,etc.
  * You can use upper case Booleans like AND, OR and NOT with our search term.
  * You can search events , you can even add items to the search 
  * You can also add a search from field side bar on left 
  * You can use things like count by or sort and you can pipe it | for more search results.
#### Creating reports 
  * You can edit schedule and by selecting schelule report, we are given options on when we want to run the report and what to do with the results.
    * You have the options to send an email or run a script when search finishes.
    * You can view the result with statistical data or visualization or both.
    
