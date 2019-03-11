pipeline {
     agent any
     stages {
      stage {'Build'} {
       steps {
        echo 'Running build . . .'
         sh './gradlew build --no-deamon'
         archivrArtifacts artifacts 'dist/trainSchedule.zip'
         }
        }
      }
    }
