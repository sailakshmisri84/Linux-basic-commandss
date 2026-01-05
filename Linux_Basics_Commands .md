🌱 Linux Commands – Beginner Notes

This file contains basic Linux commands with simple explanations.
It is designed for beginners and quick revision.

📂 Basic File & Directory Commands

ls - List files and directories
Example: ls

cd - Change directory
Example: cd Documents

pwd - Print working directory
Example: pwd

mkdir - Create a new directory
Example: mkdir myfolder

rmdir - Remove an empty directory
Example: rmdir myfolder

rm - Remove files or directories
Example: rm file.txt

cp - Copy files or directories
Example: cp file1.txt file2.txt

mv - Move or rename files or directories
Example: mv old.txt new.txt

touch - Create an empty file
Example: touch test.txt

📄 File Viewing Commands

cat - Display file content
Example: cat file.txt

less - View file content page by page
Example: less file.txt

head - Display first lines of a file
Example: head file.txt

tail - Display last lines of a file
Example: tail file.txt

🔍 Search & Help Commands

grep - Search for text in files
Example: grep "linux" file.txt

find - Search for files and directories
Example: find /home -name file.txt

locate - Find files by name
Example: locate file.txt

man - Display the manual of a command
Example: man ls

history - Show previously used commands
Example: history

👤 User Management Commands

useradd - Create a new user
Example: sudo useradd user1

userdel - Delete a user
Example: sudo userdel user1

usermod - Modify a user account
Example: sudo usermod -aG sudo user1

passwd - Set or change user password
Example: passwd user1

whoami - Display current logged-in user
Example: whoami

id - Display user ID and group ID
Example: id user1

👥 Group Management Commands

groupadd - Create a new group
Example: sudo groupadd developers

groups - Show groups of a user
Example: groups user1

🔐 Permissions & Ownership Commands

chmod - Change file permissions
Example: chmod 755 script.sh

chown - Change file owner
Example: sudo chown user1 file.txt

chgrp - Change group ownership
Example: sudo chgrp developers file.txt

ls -l - View file permissions
Example: ls -l

⚙️ Process & System Commands

ps - Display running processes
Example: ps

top - Show system resource usage
Example: top

kill - Terminate a process
Example: kill 1234

df - Show disk space usage
Example: df -h

du - Show directory size
Example: du -sh myfolder

free - Display memory usage
Example: free -h

🛠️ Service Management Commands (systemctl)

systemctl status service_name - Check service status
Example: systemctl status apache2

systemctl start service_name - Start a service
Example: sudo systemctl start apache2

systemctl stop service_name - Stop a service
Example: sudo systemctl stop apache2

systemctl restart service_name - Restart a service
Example: sudo systemctl restart apache2

systemctl enable service_name - Enable service at boot
Example: sudo systemctl enable apache2

systemctl disable service_name - Disable service at boot
Example: sudo systemctl disable apache2

📦 Package Management Commands

apt update - Update package list
Example: sudo apt update

apt upgrade - Upgrade installed packages
Example: sudo apt upgrade

apt install package_name - Install a package
Example: sudo apt install git

apt remove package_name - Remove a package
Example: sudo apt remove git

yum install package_name - Install package (RPM systems)
Example: sudo yum install git

🌐 Network Commands

ping - Check network connectivity
Example: ping google.com

ifconfig - Display network interfaces
Example: ifconfig

ip a - Show IP address
Example: ip a

netstat - Display network connections
Example: netstat -tuln

ssh - Connect to a remote system
Example: ssh user@192.168.1.10

scp - Copy files between systems securely
Example: scp file.txt user@192.168.1.10:/home/user

📦 Archive & Compression Commands

tar - Archive files and directories
Example: tar -cvf backup.tar myfolder

gzip - Compress files
Example: gzip file.txt

gunzip - Decompress files
Example: gunzip file.txt.gz

🧾 Text Processing Commands

cut - Extract columns from files
Example: cut -d ":" -f1 file.txt

wc - Count lines, words, characters
Example: wc file.txt

diff - Compare two files
Example: diff file1.txt file2.txt

🔗 Miscellaneous Commands

echo - Display text or variables
Example: echo "Hello Linux"

date - Display system date and time
Example: date

clear - Clear the terminal screen
Example: clear

📌 Still learning, still growing.
This repository will be updated as I continue my Linux journey.

#Linux #LinuxBasics #LearningLinux #GitHub #TechJourney
