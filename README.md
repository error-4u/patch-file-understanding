This repo is to understand the use of patch file 

   Patch file is a file used to merge the features of another branch to another branch 

To understand the use of patch file these are the following steps

Step 1

commit on both the branch main or the another branch 

Step 2 

In the feature branch make a patch file by using 

$ git format-patch master -o patch

This command wil create a patch file

Step 3
 
 Now we have to apply this feature branch on the main branch so we have to use this command

 $ git amp patch/<your patch file name>



