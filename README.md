# DuplicateFileRemover-Python #
This script periodically scans given directory and its sub directories and create list of duplicate files. After traversing directory it deletes all the duplicate files and keep one copy of it. This script also keeps log of deleted files and sends that log file to user via email.    
## Feture ##  
1.Checksum is generated by using md5 algorithm  
2.Create periodic log file of deleted files  
3.Send that log file via Email to user    
## Usage ##  
$DuplicateFileRemover Dir_Name Time_Interval[min] Mail_ID  
**.** DuplicateFileRemover : Name of script  
**.** Dir_Name : Name of Directory which may contain duplicate files  
**.** Time_Interval[min] : Time Interval for script in minuts  
**.** Mail_ID : Mail ID of reciever    
###### Tip  
Turn on **Allow less Secure apps** option in your gmail account 
