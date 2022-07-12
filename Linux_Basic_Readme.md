


#Basic Commands

1. pwd  - present work directory 
```
learn@ubuntu:~$ pwd
/home/learn
```

2. ls  - list the files
```
learn@ubuntu:~$ ls
Desktop  Downloads  Linux internals Pictures Videos  Music
file.txt file1.c file2.md
```

3. How to create a folder
 mkdir - make directory
 ```
 learn@ubuntu:~$ mkdir myfolder
 
 
 learn@ubuntu:~$ls
 Desktop  Downloads  Linux internals Pictures Videos  Music
 myfolder file.txt file1.c file2.md
```
4. How to create a file 

vim filename.(file extenstion)

 ```
 learn@ubuntu:~$vim myfile.txt 
 learn@ubuntu:~$vim myfile.cpp
 learn@ubuntu:~$vim myfile.c
 
 
 learn@ubuntu:~$ls
 Desktop  Downloads  Linux internals Pictures Videos  Music
 myfolder file.txt file1.c file2.md myfile.txt myfile.cpp myfile.c
 
 ```
 
5. How to delete file 

rm - remove 

```
 learn@ubuntu:~$rm myfile.c
 
 learn@ubuntu:~$ls
 Desktop  Downloads  Linux internals Pictures Videos  Music
 myfolder file.txt file1.c file2.md myfile.txt myfile.cpp 
```

6. How to remove folder 

rm -r (foldername)

```
 learn@ubuntu:~$rm -r myfolder
 
 learn@ubuntu:~$ls
 Desktop  Downloads  Linux internals Pictures Videos  Music
 file.txt file1.c file2.md myfile.txt myfile.cpp myfile.c
 
 ```

#Install Vim on Ubuntu

Step 1. Update the Ubuntu package database

```
  sudo apt update
```  
Step 2. Install Vim using apt
```
  sudo apt install vim
```
Step 3. Check Vim version
```
    vim --version
```


#Install G++ Compiler 

```
sudo apt install g++
```

#How to write file file in Vim editor 

step 1 : Create a file 

vim file.cpp

step 2: press insert key

step 3 : start write 

step 4 : Saving the file, Press esc key and type :w 
         Note     :w - saving the file  
                  :q! - without saving and close the file 
                  :wq - save and close the file 
				  



	