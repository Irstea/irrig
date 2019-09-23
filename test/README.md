**Testing guidelines**

Test files are located in irrig/test/[test-folder]

The test folder is in the format: tmp-[type]-[Date][Version]  
- **Type**: *rain* or *crop* or *soil*     
- **Date**: is the date of data sample  
- **Version**: testers could ignore this information.  

Example: tmp-crop-20130910d is a test folder for the Arvalis data sample for crop growth deduction of the date 10/09/2013.   

Each test folder contains three subfolders:   
- **Input**: ontology file before drools inference.  
- **Output**: ontology file after drools inference.  
- **Tmp**: testers could ignore this information.  
