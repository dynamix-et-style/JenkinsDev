pipeline {
   agent { label 'jdk8' }
   environment {
      MY_NAME = 'Mary'
   }
   stages {
      stage('Say Hello') {
         steps {
            echo 'Hello ${MY_NAME}!'   
            sh 'java -version'
         }
      }
   }
}
