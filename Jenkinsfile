pipeline{
  agent any
  stages{
    echo 'running Tests'
    sh 'mvn test'
    }
   }
   stage('Build'){
   steps{
   echo 'Building jar files...'
   sh 'mvn package'
   }
   }
   }
   }
