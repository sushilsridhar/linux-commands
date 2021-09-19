# linux

Linux is kernel  
kernel is a system software within the operating system  
Unix is operating system

# linux-commands  

### 1. File related   
**creates a new file**   
touch newFile.txt 

**open a file**  
nano newFile.txt  

**create and insert into a file**   
cat > newFile.txt  

**remove a file**  
rm newFile.txt

### 2. Set Path

open ~/.bash_profile  

**Java Path Setup for example**  
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_112.jdk/Contents/Home  
export PATH=$PATH:JAVA_HOME

**for changes to reflect immediately**  
source ~/.bash_profile


-----------------
view hidden file

ls -ld .?* 

32 bit or 64 bit

getconf LONG_BIT

Directory Operations

Move,remove a file, directory

mv file_1.txt /home/pungki/office

mv directory_1/ /home/pungki/office/

rm file
rm directory


Remove Folder:

To remove the folder with all its contents(including all interior folders):

rm -rf /path/to/directory
