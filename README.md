# linux

Linux is kernel  
kernel is a system software within the operating system  
Unix is operating system

# linux-commands  

### 1. Servers
**Apache Tomcat Server**  
./startup.sh  
./shutdown.sh 
  
**Apache HTTP Server** 

sudo apachectl start  
sudo apachectl stop  
sudo apachectl restart  

**Json Server**   
start server  
json-server --watch db.json -p 3001 -d 2000  

### 2. File and Directory operations   
**creates a new file**   
touch newFile.txt 

**open a file**  
nano newFile.txt  

**create and insert into a file**   
cat > newFile.txt  

**remove a file**  
rm newFile.txt  

**create**  
mkdir dir_name  

**move**  
mv file_1.txt /home/username/office
mv directory_1/ /home/username/office/

**remove**  
rm file  
rm directory  
rm -rf /path/to/directory - removes all sub folders too  

### 3. Utilities

**Kill a process**   
lsof -i:8080  
kill (pid of process)
  
**Get IP Address**   
ipconfig getifaddr en0

**View hidden file**   
ls -ld .?*  

**32bit or 64bit system**   
getconf LONG_BIT  

### 4. Set Path

open ~/.bash_profile  

**Java Path Setup for example**  
export JAVA_HOME=/Library/Java/JavaVirtualMachines/jdk1.8.0_112.jdk/Contents/Home  
export PATH=$PATH:JAVA_HOME

**for changes to reflect immediately**  
source ~/.bash_profile  
