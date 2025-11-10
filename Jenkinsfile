pipeline {
  agent any
    
  stages {
    stage('checkout') {
      steps {
        git branch: 'main', url:"https://github.com/1ms24mc011/test"
      }
    }

    stage('Build') {
      steps {
          echo "Building.........."
      }
    }

    stage('test') {
       steps {
         echo "Testing....."
       }
     }
   }
}
