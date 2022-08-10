This error frustate everyone when one try to use pip in the Power shell, command Promot or Visual Code.To solve this error on windows, you must declare path variable by following these steps:

Step 1 - Right click on My Computer or This PC
Step 2 - Click on Properties
Step 3 - Click on Advanced System Settings

You will find a section called system variables.
Click on Path from the list of variable and values that shows up there.

After clicking on path click Button Click on edit. You will find a New button in the pop up.

Click that and paste the location of the python35 or python36 folder (The location you specified while installing python) followed by \Scripts there.

For me its C:\Users\a610580\AppData\Local\Programs\Python\Python35-32 so I type C:\Users\a610580\AppData\Local\Programs\Python\Python35-32\Scripts

Click Ok to close all windows and restart your command prompt.



if you have already set the path correctly and still getting the same error then just follow this:

Step 4 open your vs code and create a new project and copy all the code from code.txt File.
Step 5 Name this project as get-pip.py and run the code in vs code.
Step 6 pip will get downloaded at the location where you create have set the path for saved projects of your vs code
Step 7 Copy get-pip.py into your main python folder.

Congratulation 
