pipeline {
   agent any

   stages {
      stage('Print hello and hostname') {
         steps {
            echo 'Hello World'
            sh 'hots name'
         }
      }
      stage('Check OS type and version'){
          steps{
              echo 'print file os-release'
              sh 'cat /etc/os-release'
          }
      }
      stage('Execute code'){
          steps{
              echo 'execute app code'
              sh 'cat superAwesomeCode.txt'
          }
      }
   }
}
