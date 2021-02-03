# gradleinstallation

1. download gradle on /opt/tmp

wget https://services.gradle.org/distributions/gradle-6.8.1-all.zip

2. Create gradle directory
mkdir /opt/gradle

3.Unzip the gradle to /opt/gradle
$ unzip -d /opt/gradle gradle-6.8.1-bin.zip


4. Export the gradle to the PATH enviroment variable

export PATH=$PATH:/opt/gradle/gradle-6.8.1/bin
