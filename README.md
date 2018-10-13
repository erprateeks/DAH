MISSING COMMANDS in DAH - 

Reload the shell - 

source ~/.bashrc

After setting up Python env variables - 

sudo apt-get install build-essential git libreadline-dev zlib1g-dev libssl-dev libbz2-dev libsqlite3-dev

IntelliJ installation - 


1.	Download the free version of IntelliJ from  https://download.jetbrains.com/idea/ideaIC-2018.2.4.tar.gz

2.	Extract and move the output by typing the following in a command window

a.	tar -zxf ideaIC-2018.2.4.tar.gz

b.	sudo mv idea-IC-182.4505.22 /usr/local/

c.	
Run the following command which will install and configure IntelliJ
d.	/usr/local/idea-IC-182.4505.22/bin/idea.sh

Check the box to install a Desktop Icon for all users

Check the box to install shortcut link
Install the Scala plugin when prompted

Use defaults for all other options

DA SDK Installation - 

Add da environment variable

nano ~/.profile

bash '/home/prateek/Downloads/da-cli-104-984d2adddf-linux.run'

da setup

sudo ln -ns "/home/prateek/.da/bin/da" /usr/local/bin/da



