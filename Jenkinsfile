/* Jenkinsfile (Declarative Pipeline) */
/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                ansiColor('xterm') {
                   sh 'echo "Hello World"'
                    sh '''
                        echo "Multiline shell steps works too!"
                        ls -lah
                    ''' 
                }
                
            }
        }
    }
}
