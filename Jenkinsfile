pipeline {
    agent any
    stages 
{
        stage('gIT checkout') 
      {
            steps {

               git branch: 'main', url: 'https://github.com/Sonu-sharma92/Digitalink-Project.git'
          }

        }
         stage('build') {
            steps {
               sh 'docker build -t sonusharmadocker/digitalink .'
               echo 'successfully created docker image'

          }
       
       }         
    }
}
