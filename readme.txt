We all know that to organize all these manually, it's so boring and time taking task.
So we will write a python script to automatically organize these files according to the extension.


First of all we need to import the required modules.
For this we will need os and shutil modules which are in-built.
We will create a variable called path which takes the input of the directory path.
And then create a variable file which consists of a list of files.
Now we will write a for loop condition.
Using for loop we traverse through every file from files.
Then we split the filename and extension of the file.
We only need the extension name, so we remove the dot from the extension through slicing.
And then we need to write if statement.
If the extension directory already exists, then we move the file to that directory.
In else statement, we make a new directory and then we move the file into it.

Through this code it is so easy to organize our files.
The code automatically organizes the files.



 