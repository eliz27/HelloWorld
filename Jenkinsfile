  
pipeline {
   agent any
   stages {
      stage('FirstFile') {
        steps {  
             git 'https://github.com/eliz27/HelloWorld.git'
             sh 'cat HelloWorld.py'
             echo "first print"
        }
      }
   }
}
