pipeline {
  agent any
  stages {
    stage('check') {
      steps {
        sh '''mkdir /tmp/test1
cd /tmp/test1
wget --no-cookies --no-check-certificate --header "Cookie: gpw_e24=http%3A%2F%2Fwww.oracle.com%2F; oraclelicense=accept-securebackup-cookie" "http://download.oracle.com/otn-pub/java/jdk/8u172-b11/a58eab1ec242421181065cdc37240b08/jdk-8u172-linux-x64.rpm"'''
      }
    }
  }
}