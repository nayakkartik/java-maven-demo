pipeline {

 agent any

 stages {

  stage('Checkout') {
   steps {
    git 'https://github.com/nayakkartik/java-maven-demo.git'
   }
  }

  stage('Build') {
   steps {
    sh 'mvn clean package'
   }
  }

 }

}