pipeline {
      agent any
      stages {
            stage('Init') {
                  steps {
                        echo 'Hi, this is Johnson from LevelUp360'
                        echo 'The Test will start soon'
                  }
            }
            stage('Build') {
                  steps {
                        echo 'Building Sample Maven Project'
                  }
            }
            stage('Deploy') {
                  steps {
                        echo "Deploying in Staging Area - TOMCAT"
                  }
            }
            stage('Deploy Production') {
                  steps {
                        echo "Deploying in Production Area- TOMCAT"
                  }
            }
      }
}