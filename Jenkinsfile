node('slave') {
     stage ('Checkout'){

         checkout scm
      }
stage('gradle build'){
 def gradleHome = tool 'gradle4'
      
      sh "${gradleHome}/bin/gradle clean install"
      }
