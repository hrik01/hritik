# <a name="_a5vi8rhp4nyi"></a>Linux Assignment 4



**Q1. Create a directory named "MyFiles" in your home directory. Navigate into this directory and list its contents.**

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 001](https://github.com/hrik01/hritik/assets/141578720/a166171b-5035-42fc-9471-4d389cde2427)
![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 002](https://github.com/hrik01/hritik/assets/141578720/14f26198-7c77-47ea-b507-f2659aaff233)
![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 003](https://github.com/hrik01/hritik/assets/141578720/e0b4b769-097d-4ed0-a673-840ff3f60d1a)


![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.001.png)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.002.png)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.003.png)




**Q2.Copy a file named "document.txt" from your home directory to the "MyFiles" directory. Move the file to a subdirectory named "Documents" within "MyFiles."**
![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 004](https://github.com/hrik01/hritik/assets/141578720/0595f907-222a-478c-9dc7-a5912d9236c7)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.004.png)


**Q3.Create an empty file named "notes.txt" in the "MyFiles" directory. Afterward, delete the file.**
![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 005](https://github.com/hrik01/hritik/assets/141578720/da9d6e1b-3112-40bf-b2ef-8b6772018f79)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.005.png)




**Q4.Create a hard link named "hardlink.txt" for the file "document.txt" within the "Documents" subdirectory. Also, create a symbolic link named "symlink.txt" in the same location.**
![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 006](https://github.com/hrik01/hritik/assets/141578720/5e5bdf9c-03ea-4fc9-ace9-07b8e44a6fa0)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.006.png)





**Q5 .In the "MyFiles" directory, use a single command to list all files that start with the letter "a" and have a ".txt" extension.**

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 007](https://github.com/hrik01/hritik/assets/141578720/97099a70-6fec-409b-bef2-1cf11257fa9c)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.007.png)




**Q6.Rename all files in the "Documents" subdirectory of "MyFiles" with a ".bak" extension. Ensure the original file names are preserved.**
![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 008](https://github.com/hrik01/hritik/assets/141578720/34451e15-d453-429e-b829-2f7af2a83b6e)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.008.png)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 009](https://github.com/hrik01/hritik/assets/141578720/31669c8d-4545-4eb2-b712-35d8ec11c64a)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.009.png)



**Q7.Use a wildcard character to copy all files from the "Documents" subdirectory of "MyFiles" to another directory named "Backup."**

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 010](https://github.com/hrik01/hritik/assets/141578720/498479d7-be35-4293-b28e-47b85205c1d4)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.010.png)




**Q8.Execute the ls command to list files in the current directory. Save the output to a file named "file\_list.txt." Then, use a pipe to filter the output through grep to display only files with a ".txt" extension.**

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 011](https://github.com/hrik01/hritik/assets/141578720/1723934b-8d9d-42d3-91a4-52cfc4c75c00)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 012](https://github.com/hrik01/hritik/assets/141578720/54d8b303-1bd6-4f6b-9e79-460a9c4e2394)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.011.png)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.012.png)




**Q9.Create a new text file named "my\_notes.txt" using the touch command. Open the file in the Vim editor, add some text, and save the changes.**

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 013](https://github.com/hrik01/hritik/assets/141578720/868abcc4-e6a6-475e-8c57-28f22f7d39e3)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.013.png)



**Q10Run the date command and store the output in a variable named "current\_date." Display the value of the variable and append it to the "my\_notes.txt" file.**

$ current\_date=$(date)

$ echo "Current Date: $current\_date"

$ echo "$current\_date" >> my\_notes.txt

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.014.png)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 014](https://github.com/hrik01/hritik/assets/141578720/9a47138c-c287-4ac9-9d31-8068c7c9acf8)





**Q11. Edit the Bash startup script (e.g., .bashrc) to set an environment variable named "CUSTOM\_PATH" to a specific directory path. Ensure the variable is available in new shell sessions.**

$ vim ~/.bashrc

$ export CUSTOM\_PATH=/home/MyFiles/

$ source ~/.bash\_profile

$ echo $CUSTOM\_PATH

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 015](https://github.com/hrik01/hritik/assets/141578720/7734b26c-4b7b-4d1b-8eec-136dafc525ba)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.015.png)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 016](https://github.com/hrik01/hritik/assets/141578720/c9cf4c16-410c-4567-99c8-bab293d2df7c)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.016.png)



**Q12 Use the echo command to add a new line of text to the "my\_notes.txt" file without overwriting existing content. Verify that the new text is appended.**

$ echo "This is a new line of text." >> my\_notes.txt

$ cat my\_notes.txt

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 017](https://github.com/hrik01/hritik/assets/141578720/d13bb362-1577-4c4f-8d6f-b6a1a4cb631b)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.017.png)


**Q13  List all files in the "/etc" directory, filter the output to include only those containing the word "conf," and save the result to a file named "conf\_files.txt."**

$ ls /etc | grep "conf" > conf\_files.txt

$ cat conf\_files.txt

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 018](https://github.com/hrik01/hritik/assets/141578720/9c1ec130-97cd-46ad-a6ac-d6d96d1d0961)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.018.png)

**Q14. Open the "my\_notes.txt" file in Vim. Use Vim's search and replace functionality to replace all occurrences of the word "important" with "critical." Save the changes.**

$ vim my\_notes.txt

$ :%s/important/critical/g

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 019](https://github.com/hrik01/hritik/assets/141578720/cc5e2056-d95b-41ff-ba04-6f2a8afd1327)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.019.png)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 020](https://github.com/hrik01/hritik/assets/141578720/a2cef007-9d11-405f-8f07-50de39690cfd)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.020.png)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 021](https://github.com/hrik01/hritik/assets/141578720/0baf8c6c-dd40-4e2f-9650-4c77187a1e4e)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.021.png)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 022](https://github.com/hrik01/hritik/assets/141578720/c224a8b8-6690-4473-9248-bcb14633d864)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.022.png)



**Q15 Create a new user account named "john\_doe." Set the user's home directory to "/home/john\_doe" and assign the user to the "users" group.**

$ sudo useradd -m -d /home/hritik2 -g users hritik2

$ sudo passwd 

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 023](https://github.com/hrik01/hritik/assets/141578720/a2d852ad-ee73-472a-b170-17b1df967506)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.023.png)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 024](https://github.com/hrik01/hritik/assets/141578720/92977bf0-839a-4719-bd70-022806b3028f)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.024.png)





**Q16 Add the user "john\_doe" to the sudoers file, allowing them superuser privileges. Confirm that "john\_doe" can execute commands with sudo.**

$ sudo visudo

$ hritik2   ALL=(ALL:ALL) ALL

$ sudo echo "Hello, I have sudo privileges!"

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 025](https://github.com/hrik01/hritik/assets/141578720/b3bf2fa7-6594-4e8a-8fde-febb56708f17)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.025.png)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 026](https://github.com/hrik01/hritik/assets/141578720/d143e0f7-49fb-4aa3-8f70-c07e92d76329)

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 027](https://github.com/hrik01/hritik/assets/141578720/8adb2c08-831a-423e-ab1b-1376b64c7368)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.026.png)![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.027.png)










**Q17 Modify the user account "john\_doe" to change the default shell to "/bin/bash" and set the account's expiration date to one month from today.**

$ sudo chsh -s /bin/bash john\_doe

$ sudo chage -E $(date -d "+1 month" +%Y-%m-%d) hritik2 

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 028](https://github.com/hrik01/hritik/assets/141578720/8b53a40e-151e-4a5c-b6f6-ebd1f2c37549)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.028.png)




**Q18 :Create a new group named "development\_team." Add "john\_doe" to this group and verify the group's existence.**

$ sudo addgroup development\_team

$ sudo adduser hritik2 development\_team

$ grep development\_team /etc/group

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 029](https://github.com/hrik01/hritik/assets/141578720/4369408e-d84e-4318-b6c0-8d3b08e37cad)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.029.png)




**Q19 Remove "john\_doe" from the "users" group and add them to the "development\_team" group. Confirm the changes.**

$ sudo deluser john\_doe users

$ sudo adduser john\_doe development\_team

$ id john\_doe




**Q20 Delete the user account "john\_doe" and ensure that their home directory is also removed.**

$ sudo userdel -r john\_doe

$ ls /home/hritik2

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 030](https://github.com/hrik01/hritik/assets/141578720/6f66de16-6dd3-4844-930d-c0534b998481)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.030.png)



**Q21 Delete the group "development\_team" and ensure that all users previously belonging to the group are appropriately handled.**

$ grep development\_team /etc/group

$ sudo groupdel development\_team

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 031](https://github.com/hrik01/hritik/assets/141578720/4affedd9-0a10-49ed-81cc-097581220ee3)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.031.png)



**Q22 Implement a password policy that requires users to change their passwords every 90 days. Apply this policy to all existing and new user accounts.**

$ sudo chage -M 90 -m 0 -W 7 -I 30 -E -1 $(cut -d: -f1 /etc/passwd)

$ sudo vim /etc/login.defs

Inside this file add max pass day as 90 and min pass day as 0

PASS\_MAX\_DAYS   90

PASS\_MIN\_DAYS   0

![Aspose Words 0cae80d6-16eb-4561-8c90-541f15eced1b 032](https://github.com/hrik01/hritik/assets/141578720/64792f19-544f-4392-ad9f-3974d1346267)

![](Aspose.Words.0cae80d6-16eb-4561-8c90-541f15eced1b.032.png)


**Q23  Manually lock the user account "john\_doe." Attempt to log in as "john\_doe" to confirm that the account is locked. Then, unlock the account.**

$ sudo passwd -l hritik2

$ su - hritik2

$ sudo passwd -u hritik2



**Q24 Use the id command to display detailed information about the "john\_doe" user, including user ID, group ID, and supplementary groups.**

$ id hritik2

$ id -u hritik2

$ id -g hritik2

$ id -G hritik2




**Q25  Configure the password aging for the user "john\_doe" to enforce a maximum password age of 60 days. Confirm that the changes take effect.**

$ sudo chage -M 60 hritik2

$ sudo chage -l hritik2








** 	































