pipeline {
    agent any
    environment {
        PATH="/usr/share/maven/bin/:$PATH"
    }
    stages {
        stage('Fetch code') {
            steps {
               // echo 'Hello World'
               git 'https://github.com/Naveenkumarb808/hello-world-war.git'
            }
        }
        stage('build code') {
            steps {
               // echo 'Hello World'
               sh "mvn clean package"
            }
        }
    }
}
