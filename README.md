## Rebate Record Maintaining Program.

This program maintains records of rebates that are turned in by buyers.  
It operates in five modes:  
First, it will look up a rebate given the first name, last name, and phone number.  
This combination of buyer info is unique to each buyer.  
Second, you can add a rebate to the file that holds all of the rebate records.  
Third, you can modify any info of a rebate on record.  
Fourth, you can delete any record on file first by either clicking on the list or  
by running a search and then clicking delete.  
Fifth, you can clear the fields of the form at any time you wish.  

The file used is named "CS6326Asg2.txt" and it can be found in the Project folder:  
"Asg2-nsd093020/Asg2-nsd093020/bin/Debug"  
The program will create it for you if it doesn't exist.  
Each new record added to the file will have three hidden fields at the end of each recorded:  
-time of first record edit    -time of record save    -number of times user used backspace  
These fields never change after a record is added.  
You can navigate through the UI by clicking, tabbing, or using alt shortcuts.  
  
## Rebate Data Analyzer Program.

This program analyzes records of rebates that have been previously added to Rebate Record Maintenance system.  
 
It operates in two modes:  
First, you can select the record file you wish to analyze and the prgram will show its results in the textbox below.  
Second, you can save the results to a file with default settings or you can set the location and filename.  

The file to be analyzed is expcted to be in the format of the rebate record file:  
firstName \t middleInitial \t lastName \t addressLine1 \t addressLine2 \t city \t state \t zipcode \t  
gender \t phone \t email \t ProofOfPurchase \t Date \t timeStart \t timeAdd \t backStrokes  
 
You can select thise file by either:  
 a) typing in the address to the file in the Record File Path textbox and clicking Open  
 b) clicking Browse and browsing to the desired file using a Windows File dialog  
 
The results shown will be in the format:  
  Number of records:          10  
	Minimum entry time:         1:12  
	Maximum entry time:         2:06  
	Average entry time:         1:37  
  Minimum inter-record time:  0:03  
	Maximum inter-record time:  0:9  
	Average inter-record time:  0:05  
	Total time:                 16:12  
	Backspace count:            14  
 This is the same format that will be used if you wish to save the results to a file.  

You can save the results to a file by:  
 a) leaving the default directory and filename unchanged in the Data Results File Path textbox and clicking Save  
 b) typing in a custom address and/or file name in the same textbox  
 c) clicking Browse and browsing to the desired directory by using a Windows File dialog  
    and either leave the filename unchanged or customize it  
