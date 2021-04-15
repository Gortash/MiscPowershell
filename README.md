# MiscPowershell
Miscellaneous Powershell Scripts

------------------FindAndZip--------------------
Contains two functions:
  1. print_unused_files
    Recieves two parameters: an integer representing the minimum number of days acceptable since the last access of a file, the path to the folder from which to execute
      Finds any non-folder type file which has not been accessed within the number of days entered as a parameter and prints its location to the console along with the 
      number of days since it has been accessed. The function is then recursively called on all sub-folders.
      
      
  2. zip_unused_files
    Recieves two parameters: an integer representing the minimum number of days acceptable since the last access of a file, the path to the folder from which to execute
      Finds any non-folder type file which has not been accessed within the number of days entered as a parameter and prints its location to the console along with the 
      number of days since it has been accessed. Then a zipped copy of the file is created and the original file is deleted. The function is then recursively called on 
      all sub-folders.
