**Linux commands**

**1: How to make a directory?**

**Ans:**  We can make a directory using command **mkdir.**

**Output:**

```

rajshakya@thunder:~/Desktop$ mkdir React

rajshakya@thunder:~/Desktop$ ls

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  node-v20.10.0-linux-x64

Folder                                                   React

```

**Example: mkdir React**

**mkdir:** Command to create the directory.

**React:** Name of the directory.
![Alt text](<Screenshot from 2023-12-14 15-04-09.png>)


**2: How to remove a directory?**

**Ans:** we can remove a directory by using command **rmdir React.**

**Output:**

```

rajshakya@thunder:~/Desktop$ rmdir React/

rajshakya@thunder:~/Desktop$ ls

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  Folder  node-v20.10.0-linux-x64

rajshakya@thunder:~/Desktop$ 

```

**Example: rmdir React**

**rmdir:** Command to remove the directory.

**React:** Name of the directory.
![Alt text](<Screenshot from 2023-12-14 15-06-53.png>)


**3: Command to move or rename file.**

**Ans:** From mv command we can move or rename file.

**Output:**

```

rajshakya@thunder:~/Desktop$ touch raj.txt rahul.txt

rajshakya@thunder:~/Desktop$ ls

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  node-v20.10.0-linux-x64  raj.txt

Folder                                                   rahul.txt

rajshakya@thunder:~/Desktop$ mv raj.txt rahul.txt

rajshakya@thunder:~/Desktop$ ls

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  node-v20.10.0-linux-x64

Folder                                                   rahul.txt

rajshakya@thunder:~/Desktop$ 

```

**Example: mv raj.txt rahul.txt**
![Alt text](<Screenshot from 2023-12-14 15-12-07.png>)

**mv raj.txt rahul.txt:** This command rename the file(raj.txt to rahul.txt)
![Alt text](<Screenshot from 2023-12-14 15-18-54.png>)

**Example: mv rahul.txt Folder**(In this command we are moving rahul.txt file into the Folder directory)

**Output:**

```
rajshakya@thunder:~/Desktop$ mv rahul.txt Folder

rajshakya@thunder:~/Desktop$ ls

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  Folder  node-v20.10.0-linux-x64

rajshakya@thunder:~/Desktop$ cd Folder/

rajshakya@thunder:~/Desktop/Folder$ ls

rahul.txt

rajshakya@thunder:~/Desktop/Folder$

```



**4: How to make a copy of a file?**

Ans: we can make a copy of a file by using command **cp**. 

**Example: cp raj1.txt raj2.txt** 

**Cp: command to copy the file**.
**Index.txt:** Name of the file.
![Alt text](<Screenshot from 2023-12-14 17-12-15-1.png>)

Output:

```
rajshakya@thunder:~/Desktop$ cp raj1.txt raj2.txt 

rajshakya@thunder:~/Desktop$ ls

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  raj1.txt

Folder                                                   raj2.txt

node-v20.10.0-linux-x64

rajshakya@thunder:~/Desktop$ vim raj2.txt 

rajshakya@thunder:~/Desktop$ 

```

**5:** How to create an empty file?

**Ans:** we can create an empty file by using command **touch**.

Output:

```
rajshakya@thunder:~/Desktop$ touch raj.html

rajshakya@thunder:~/Desktop$ ll -ld

drwxr-xr-x 4 rajshakya rajshakya 4096 Dec 14 17:43 ./

rajshakya@thunder:~/Desktop$ 

```

**Example: touch raj.html**

![Alt text](<Screenshot from 2023-12-14 15-21-31.png>)


**6:** Command to remove multiple files with a single command.

**Ans:** By using **mv** command we can remove multiple files.


Output:

```
rajshakya@thunder:~/Desktop$ ls

a10.txt  a6.txt                                                   node-v20.10.0-linux-x64

a1.txt   a7.txt                                                   raj1.txt

a2.txt   a8.txt                                                   raj2.txt

a3.txt   a9.txt                                                   raj.html

a4.txt   chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop

a5.txt   Folder

rajshakya@thunder:~/Desktop$ rm a{1..10}.txt

rajshakya@thunder:~/Desktop$ ls

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  raj1.txt

Folder                                                   raj2.txt

node-v20.10.0-linux-x64                                  raj.html

rajshakya@thunder:~/Desktop$ 
```

**Example: rm a{1..10}.txt**
![Alt text](<Screenshot from 2023-12-14 16-56-36.png>)


7:Remove content from the folder without removing folder.

Ans:We can remove the content from the folder by using command  **rm file\_name.**

Output:

```

rajshakya@thunder:~/Desktop$ ls

brijesh.html                                             node-v20.10.0-linux-x64

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  raj.html

Folder                                                   sumit.html

rajshakya@thunder:~/Desktop$ rm brijesh.html raj.html sumit.html 

rajshakya@thunder:~/Desktop$ ls

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  Folder  node-v20.10.0-linux-x64

rajshakya@thunder:~/Desktop$ 

```

**Example: rm brijesh.html raj.html sumit.html**
![Alt text](<Screenshot from 2023-12-14 16-51-29.png>)


**8:**Createmultiple folder (a-z) with a single command.

**Ans:** By using command **mkdir {a..z}** , multiple files will be created.

Output:

```

rajshakya@thunder:~/Desktop$ ls

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  Folder  node-v20.10.0-linux-x64

rajshakya@thunder:~/Desktop$ mkdir {a..z}

rajshakya@thunder:~/Desktop$ ls

a                                                        g  node-v20.10.0-linux-x64  v

b                                                        h  o                        w

c                                                        i  p                        x

chrome-hbblfifohofgngfbjbiimbbcimepbdcb-Default.desktop  j  q                        y

d                                                        k  r                        z

e                                                        l  s

f                                                        m  t

Folder                                                   n  u

rajshakya@thunder:~/Desktop$ 

```

**Example:mkdir {a..z}**

![Alt text](<Screenshot from 2023-12-14 17-02-54.png>)






