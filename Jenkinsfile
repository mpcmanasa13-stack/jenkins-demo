pipeline {
     agent any

    stages {

         stage('Clone') {
             steps {
                  git url: 'https://github.com/mpcmanasa13-stack/jenkins-demo',
                      branch: 'main'
           }
      }

       stage('Run Script'){
          steps {
              sh 'chmod +x script.sh'
              sh './script.sh'
       }
     }
  }
}
