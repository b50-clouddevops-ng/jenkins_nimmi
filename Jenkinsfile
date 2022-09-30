pipeline {
       agent any
    // agent {label : Jenkins } 
    //    

    triggers { pollSCM('*/2 * * * *') }

    tools {
        maven 'maven-3.8.5'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Hi') {
            steps {
                sh " echo Run mvn command"
                sh "mvn clean"
            }
        }
        
    }
}