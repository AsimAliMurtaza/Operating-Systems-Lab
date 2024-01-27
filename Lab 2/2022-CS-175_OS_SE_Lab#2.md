# **Operating System Lab 2 Manual**

> ![UET Logo](images/UET Logo.png)

**Session: 2022 – 2026**

> **Submitted by:**
>
> Asim Ali Murtaza 2022-CS-175
>
> **Supervised by:**
>
> Mr. Nauman Shafi
>
> Department of Computer Science

## 			

> ## **University of Engineering and Technology**
>
> **Lahore Pakistan**



# Table of Content

[TOC]



#### **Task 1:**

**Ubuntu Installation on Virtual Box and Installing Compilers:**

##### **Step 1:**

Add Ubuntu ISO image to Virtual Box. The VM will power up automatically and the following booting screen will show.

![VirtualBox_Ubuntuu_26_01_2024_08_41_40](images/VirtualBox_Ubuntuu_26_01_2024_08_41_40.png)

##### **Step 2:**

After that, The ubuntu will start.

![VirtualBox_Ubuntuu_26_01_2024_08_41_50](images/VirtualBox_Ubuntuu_26_01_2024_08_41_50.png)

##### **Step 3:**

Then the screen will show up.

![VirtualBox_Ubuntuu_26_01_2024_08_44_47](images/VirtualBox_Ubuntuu_26_01_2024_08_44_47.png)

##### **Step 4:**

Here select your language and click on install Ubuntu.

![VirtualBox_Ubuntuu_26_01_2024_08_48_58](images/VirtualBox_Ubuntuu_26_01_2024_08_48_58.png)

##### **Step 5:**

Here select your language and keyboard layout. Then click continue.

![VirtualBox_Ubuntuu_26_01_2024_08_50_56](images/VirtualBox_Ubuntuu_26_01_2024_08_50_56.png)

##### **Step 6:**

In this step, choose normal installation and click continue.

![VirtualBox_Ubuntuu_26_01_2024_08_54_43](images/VirtualBox_Ubuntuu_26_01_2024_08_54_43.png)

##### **Step 7:**

Select erase disk and install Ubuntu. Then click install now.

![VirtualBox_Ubuntuu_26_01_2024_08_55_05](images/VirtualBox_Ubuntuu_26_01_2024_08_55_05.png)

##### **Step 8:**

Choose your username, machine’s name, and password for your login account. Click continue.

![VirtualBox_Ubuntuu_26_01_2024_08_56_40](images/VirtualBox_Ubuntuu_26_01_2024_08_56_40.png)

##### **Step 9:**

Now just wait for the installation to finish. It will take around 20-30 minutes depending on your allocated resources.

![VirtualBox_Ubuntuu_26_01_2024_08_57_19](images/VirtualBox_Ubuntuu_26_01_2024_08_57_19.png)

##### **Step 10:**

After installation is finished. It will ask to restart the computer. Click restart now and let it reboot.

![VirtualBox_Ubuntuu_26_01_2024_09_12_53](images/VirtualBox_Ubuntuu_26_01_2024_09_12_53.png)

##### **Step 11:**

Now after rebooting, it will ask you to enter your password that you chose earlier. Enter your password and press the enter key.

![VirtualBox_Ubuntuu_26_01_2024_09_17_37](images/VirtualBox_Ubuntuu_26_01_2024_09_17_37.png)

##### **Step 12:**

Congratulation! You have successfully installed Ubuntu on your Virtual Box.

![VirtualBox_Ubuntuu_26_01_2024_09_25_57](images/VirtualBox_Ubuntuu_26_01_2024_09_25_57.png)

##### **Step 13:**

Open Terminal on your newly installed Ubuntu. A Terminal window will appear.



##### **Step 14:**

Install GCC compiler by typing the command "sudo apt install gcc". 

You will be prompted to continue to download the gcc. Type y and press enter key. The gcc compiler will begin downloading and installing. After successfully installing it, type gcc --version to check if it is installed properly.

![VirtualBox_Ubuntuu_27_01_2024_16_31_34](images/VirtualBox_Ubuntuu_27_01_2024_16_31_34.png)

##### **Step 15:**

Install G++ compiler by typing the command "sudo apt install g++". 

You will be prompted to continue to download the g++. Type y and press enter key. The g++ compiler will begin downloading and installing in the same fashion as gcc. After successfully installing it, type g++--version to check if it is installed properly.

![VirtualBox_Ubuntuu_27_01_2024_16_41_52](images/VirtualBox_Ubuntuu_27_01_2024_16_41_52.png)



#### **Task 2:**

**Testing of GCC and G++ Compilers on Ubuntu:**

##### **Step 1:**

Open any code editor of your choice and create a file named "test.cpp", and enter the following code in it.

```c++
#include <iostream>

using namespace std;

int main(){

	cout << "Testing G++ Compiler!!!" << endl;

	return 0;

}
```

##### **Step 2:**

Now go to your terminal and compile your written code using the following commands:

g++ -o obj test.cpp

Then run it

./obj

and confirm the output.

![VirtualBox_Ubuntuu_27_01_2024_16_57_59](images/VirtualBox_Ubuntuu_27_01_2024_16_57_59.png)

##### **Step 3:**

Now create another file named "test.c", and enter the following code in it.

```c
#include <stdio.h>

void main(){

	printf("Testing gcc Compiler!!!!!\n");

}
```

##### **Step 4:**

Now go to your terminal and compile your written code using the following commands:

gcc -o obj test.c

Then run it

./obj

and confirm the output.

![VirtualBox_Ubuntuu_27_01_2024_17_00_20](images/VirtualBox_Ubuntuu_27_01_2024_17_00_20.png)

That's it! You have successfully installed and tested both compilers.



**GitHub Repository Link**

https://github.com/AsimAliMurtaza/Operating-Systems-Lab
