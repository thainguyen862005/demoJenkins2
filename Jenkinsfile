pipeline{
  agent any
  tools{
    maven 'Maven'
    jdk 'JDK25'
  }

stages{
  stage('Build'){
    steps{
      bat 'mvn -version'
      bat 'mvn clean package'
    }
  }
}
}
