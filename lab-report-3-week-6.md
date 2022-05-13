# Lab Report 3
**Team Axolotl**
 ![Axolotl](https://user-images.githubusercontent.com/96553474/162535420-9fa77fb1-e2cc-42fb-a98d-479bef6edcd3.jpg)

 [Index Page](index.html)

### **Streamlining ssh Configuration**

```.ssh/config``` file:

![Image](configFile.png)

```ssh``` command of my login:

![Image](login.png)

```scp``` command to copy:

![Image](copySsh.png)



In this case, I simply created an ssh file to make a shortcut. It was the easiest of the three tasks, but finding the ssh folder on a mac proved to be quite the challenge. It works well, and I chose ```ieng6``` to be my alias.

### **Setup Github Access from ```ieng6```**
Picture of where my key is stored on github:
![Image](gitKeyStorage.png)
Picture of my key in my user account:
![Image](localKey.png)
Picture of my key in my user account:
![Image](localKeyStorage.png)
Git commands for push and commit respectively
![Image](GitPush.png)

![Image](GitCommit.png)

[Link](https://github.com/dfigueroag/markdown-parser/commit/a5de5996d2d29a48e827b530b5d21356ef47527b) to resulting commit.



This portion deemed to be a lot more challenging as my computer was not liking the git commands. After tutor hours, this issue was promptly fixed. The results were as expected and they work fine.

### **Copy whole directories with ```scp -r```**
Copying whole markdown-parse directory to ```ieng6``` account:
![Image](copyingEverything.png)
![Image](copyingEverythingPt2.png)

Logging into ```ieng6``` and running tests for repository:
![Image](tests.png)

Combining ```scp```, ```;```, and ```ssh``` to copy the whole directory and run the tests in one line:
![Image](commandLine.png)
![Image](resultWithTest.png)


This portion was also straight forward. No issues where encountered once I fixed my key in part 2. The command line was tedious, but it worked in the end. This allows the process to be streamlined and works well.