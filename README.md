# jmeter

Tasktestplan.jmx is the jmeter script for “WebstaurantStore Scratch and Dent Outlet.” in this script /outlet page is opened and a random option is selected from the list and then a random product is selected from the listpage.
Step1: script was created from chrome with blazemeter chrome extension and jmx is saved and opened it in jmeter for corelation and parametrizing the script
Step2: Random values are captured from the previous response and send the value to next request (corelation) 
Step3: Assertions added for response data 
Step4: Added constant throughput timer for 5rpm 
Step5: Users added to get the 5rpm for 15mins test duration for transaction controller timer
Step6: Listerners were added to get the resutls
Step7: Ran the test and results are stored in jtl file (report2.jtl) and html file (results.zip file)
