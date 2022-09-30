pipeline {
       agent any
    // agent {label : Jenkins }     

    triggers { pollSCM('*/2****') }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }

        stage('Hi') {
            steps {
                echo 'Hi World'
            }
        }

        stage('NG WS') {
            steps {
                echo 'Hi NG ws'
            }
        }

        
    }
}