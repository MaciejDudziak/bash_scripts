clear_links - removes all symbolic links to from a catalogue and creates a log file of all links deleted  
use: ./clear_links \<path to a catalogue which will be cleared> \<path to a file in which logs will be stored>  
  
user_accounts - creates account for user with name given in parameter with home catalogue and temporary password that he is forced to change on the first log-in  
use: ./user_accounts <username>  
  
split_files - split files from one file into two files, writing every even line into second file and every odd line into third file and numering those lines  
use: ./split_files \<file which will be split> \<file that will take even lines> \<file that will take odd lines>  
  
permission - takes numerical permissions as the first parameter and gives them to all files passed as next parameters  
use: ./permissions \<numercial permission> <file1> <file2> <file3> ...  
