pipeline {
   agent any

   stages {
      stage('Verify Branch') {
         steps {
            git url: 'https://github.com/mahmoudibra96/new.git' , branch: 'main' , credentialsId: 'githubtoken'
         }
      }
   }
}