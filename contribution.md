# Install Jenkins

sudo apt-get -y install openjdk-8-jdk openjdk-8-jre

printenv

cd /etc
cat >> environment <<EOL
JAVA_HOME=/usr/lib/jvm/java-11-openjdk-amd64 
JRE_HOME=/usr/lib/jvm/java-11-openjdk-amd64/jre 
EOL

exit
                         
ssh root@X.x.x.x
                         
printenv
                         
lsb_release -a

Release:	22.10                         
                         
                         
                         
https://pkg.jenkins.io/debian-stable/                         
                         
sudo systemctl start jenkins
sudo systemctl status jenkins                         
sudo systemcrt enable jenkins                            
