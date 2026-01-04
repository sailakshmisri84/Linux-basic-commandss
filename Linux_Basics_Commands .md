# 🌱 Linux Basics -- My Learning Notes

This file contains basic Linux commands that I am learning as part of my
Linux journey. It includes the command, its description, and an example
usage.

------------------------------------------------------------------------

## 📂 File & Directory Commands

  Command   Description                    Example
  --------- ------------------------------ --------------------
  pwd       Shows current directory path   pwd
  ls        Lists files and directories    ls -l
  cd        Change directory               cd /home/user
  mkdir     Create a new directory         mkdir projects
  rmdir     Remove empty directory         rmdir test
  touch     Create empty file              touch file.txt
  rm        Remove files or folders        rm file.txt
  cp        Copy files                     cp a.txt b.txt
  mv        Move or rename files           mv old.txt new.txt

------------------------------------------------------------------------

## 📄 File Viewing Commands

  Command   Description              Example
  --------- ------------------------ ---------------
  cat       Display file content     cat file.txt
  less      View file page by page   less file.txt
  head      Show first lines         head file.txt
  tail      Show last lines          tail file.txt

------------------------------------------------------------------------

## 🔍 Search & Info Commands

  Command   Description            Example
  --------- ---------------------- ---------------------------
  grep      Search text in files   grep "linux" file.txt
  find      Find files             find /home -name file.txt
  whoami    Show current user      whoami
  history   Show command history   history

------------------------------------------------------------------------

## ⚙️ System & Process Commands

  Command   Description              Example
  --------- ------------------------ -----------
  top       Show running processes   top
  ps        Process status           ps aux
  kill      Stop a process           kill 1234
  df        Disk usage               df -h
  free      Memory usage             free -m

------------------------------------------------------------------------

## 🔐 Permissions Commands

  Command   Description          Example
  --------- -------------------- ---------------------
  chmod     Change permissions   chmod 755 file.sh
  chown     Change owner         chown user file.txt

------------------------------------------------------------------------

## 🛠️ Service Management Commands (Important)

  ------------------------------------------------------------------------
  Command           Description                     Example
  ----------------- ------------------------------- ----------------------
  systemctl status  Check service status            systemctl status
                                                    apache2

  systemctl start   Start a service                 sudo systemctl start
                                                    apache2

  systemctl stop    Stop a service                  sudo systemctl stop
                                                    apache2

  systemctl restart Restart a service               sudo systemctl restart
                                                    apache2

  systemctl enable  Start service on boot           sudo systemctl enable
                                                    apache2

  systemctl disable Disable service on boot         sudo systemctl disable
                                                    apache2

  systemctl         List active services            systemctl list-units
  list-units                                        --type=service

  service           Manage services (older systems) sudo service apache2
                                                    status
  ------------------------------------------------------------------------

------------------------------------------------------------------------

## 🚀 Package & Network Commands

  Command       Description          Example
  ------------- -------------------- ----------------------
  apt update    Update packages      sudo apt update
  apt install   Install package      sudo apt install git
  ping          Check connectivity   ping google.com
  ifconfig      Network info         ifconfig
  ip a          Show IP address      ip a

------------------------------------------------------------------------

📌 *Still learning, still growing. This file will keep expanding as I
explore more Linux!*

#LinuxBasics #LearningEveryDay #TechJourney
