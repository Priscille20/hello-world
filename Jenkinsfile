pipeline {
    agent any

    stages {
        // stage('Clone Repository') {
        //     steps {
        //         // Assuming the Go code is in a repository
        //         git 'https://your-repository-url.git'
        //     }
        // }

        stage('build') {
            steps {
                // Compile the Go code
                echo 'building the application...'
            }
        }

        stage('test') {
            steps {
                echo 'testing the application...'
            }
        }

        stage('deploy') {
            steps {
                echo 'deploying the application...'
            }
        }
    }

    // post {
    //     always {
    //         // Clean up the workspace
    //         cleanWs()
    //     }
    // }
}
