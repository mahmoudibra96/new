pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            git url: 'https://github.com/mahmoudibra96/calendar-date.git' , branch: 'main' , credentialsId: 'githubtoken'
         }
      }
   }
}