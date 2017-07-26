## Collection Pipeline in Python  
Originally published: 2016-03-16 14:45:01  
Last updated: 2016-03-16 14:45:02  
Author: Steven D'Aprano  
  
A powerful functional programming technique is the use of pipelines of functions. If you have used shell scripting languages like `bash`, you will have used this technique. For instance, to count the number of files or directories, you might say: `ls | wc -l`. The output of the first command is piped into the input of the second, and the result returned.