/* Jenkinsfile (Declarative Pipeline) */
/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                ansiColor('xterm') {
                    stage "\u001B[31mI'm Red\u001B[0m Now not"
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
