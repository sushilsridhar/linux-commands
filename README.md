# linux

Linux is kernel  
Unix is operating system

# How computer starts  
power on   
-> CPU on (POST - power on self test begin, basic diagnostic check) after diagnostic complete, sends signal to ROM    
-> BIOS (stored on ROM) initializes hardware before loading operating system, reads the hard drive, encounters the first piece of operating system, bootstrap loader     
-> bootstrap loader, loads the operating system and hand over the control to it    
-> operating system, it is loaded from hard drive to RAM (which is memory accessed by CPU) by bootstrap loader, OS's important functions are 1.Processor management 2.Memory management 3.Device management 4.Storage management 5.Application interface 6.User interface  
-> Every other programs started, are loaded into RAM for processing.

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
