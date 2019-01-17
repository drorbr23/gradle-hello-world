node('slave') {
     stage ('Checkout'){

         checkout scm
      }
stage('gradle build'){
 def mvnHome = tool 'gradle4'
      
      sh "${mvnHome}/bin/gradle clean install"
      }
      }
