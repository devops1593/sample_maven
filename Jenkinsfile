pipeline {
    agent any

    stages {
        stage ('Complie stage') {

            steps {
               withMaven(Maven : 'maven_3_6_1'){
                   sh 'mvn clean compile package'
               }
            }        
        }
       
}
        
