pipeline {
       agent any
    // agent {label : Jenkins } 
    //    

    triggers { pollSCM('*/2 * * * *') }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Hi') {
            steps {
                sh "echo 'Hai"
                sh "Run mvn command"
                sh "mvn clean"
            }
        }
        
    }
}