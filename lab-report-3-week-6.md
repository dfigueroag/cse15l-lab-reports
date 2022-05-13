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



In this case, I simply created an ssh file to make a shortcut. It was the easiest of the three tasks, but finding the ssh folder on a mac proved to be quite the challenge. It works well, and I chose ieng6 to be my alias.

### **Setup Github Access from ieng6**
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

![Image](copyingEverything.png)
![Image](copyingEverythingPt2.png)
![Image](tests.png)
![Image](commandLine.png)
![Image](resultWithTest.png)


[Code](https://github.com/kl2024/markdown-parser/blob/main/test-file3.md) that induced failure


In this case, the bug stemed from not having the required interfaces imported. Consequently when we complied the code we were met with ```illegal start of expression``` and ```cannot find symbol errors```. to debug this, we imported the ```ArrayList``` and ```List``` interfaces.