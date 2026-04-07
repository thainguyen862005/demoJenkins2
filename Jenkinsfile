pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        bat 'mvn -version'
        bat 'mvn clean package'
        echo 'Dang bien dich ma nguon'
      }
    }

    stage('Test') {
      steps {
        echo 'Kiem thu thanh cong'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Trien khai len server hoan tat'
      }
    }

  }
  tools {
    maven 'Maven'
    jdk 'JDK25'
  }
}