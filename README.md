# webapp
BUILDING WEBAPP USING MAVEN
Step 1:Maven Installation steps for Ubuntu
sudo apt-get update
sudo apt-get upgrade -y
sudo apt install wget nano tree unzip git -y
sudo apt install default-jdk -y

Step 2.: Install Maven.sh: Download the Maven Software
sudo wget https://dlcdn.apache.org/maven/maven-3/3.8.8/binaries/apache-maven-3.8.8-bin.zip
sudo unzip apache-maven-3.8.8-bin.zip 
sudo rm -rf apache-maven-3.8.8-bin.zip
sudo mv apache-maven-3.8.8/ maven

Step 3. Set Environmental Variable: Setting the home of Maven  -
#vi ~/.bash_profile
sudo vi ~/.bash_profile
export M2_HOME=/opt/maven
export PATH=$PATH:$M2_HOME/bin

source ~/.bash_profile
Step 4. Check the Maven version:
mvn -version
git clone https://github.com/JOMACS-IT/web-app.git


step 5:
mvn clean
![Screenshot (17)](https://github.com/user-attachments/assets/4cb13a79-ce64-4726-a105-4829f0a82566)

mvn package



