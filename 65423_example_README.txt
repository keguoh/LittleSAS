Questions or problem reports concerning this material may be sent to the author from the Author Page here:                  
                                                               
http://support.sas.com/publishing/authors
                                                               
If you prefer, you can send email to:  saspress@sas.com        
Use this for subject field:                                    
    Comments for <insert Author name>                                 
                                                               

While the exact details of how to handle zip files depends on whether you are on a PC or Mac, the browser you are using, and the tool you are using to unzip or decompress the file, here are some general guidelines to follow: 
                                
1.	Create a folder on your computer where you will want to store the files.
2.	Click on the .zip file on the web page.
3.	Read and accept the license agreement.
4.	From your browser, you can either save or open the downloaded zip file. 
5.	Save the file to your computer if you think you may want to unzip it again later. (This is recommended because it will save you the trouble of downloading it again from support.sas.com.)
6.	Go to the location where you saved the zip file. 
7.	Either double click or right click the zip file. 
8.	In the interface that appears, look for a button or a selection to unzip or extract the files. 
9.	You will be prompted to choose a location on your computer to put the files. Choose the folder you created for this purpose and confirm your selection.

Special considerations for users of the SAS University Edition:

Because the SAS University Edition runs in virtual UNIX environment, you need to pay special attention to where you store the unzipped files. You can either unzip the files to the myfolders directory you created when you installed the University Edition (usually C:\SASUniversityEdition\myfolders) or to another directory which you have designated as a shared folder in the virtualization software.
All references to data files in your programs need to use UNIX style paths regardless of what type of computer you are using. If you unzipped the files to your myfolders directory, then all file paths would start with ‘/folders/myfolders’. If you unzipped the files to a different shared folder, then all file paths would start with ‘/folders/myshortcuts/shortcutname’ where shortcutname is the name you gave the folder shortcut when you created it in the virtualization software.

For more details about using data files in the SAS University Edition, we highly recommend watching the video “Accessing Your Existing Data: for SAS University Edition” at http://support.sas.com/training/tutorial/studio/index.html.
