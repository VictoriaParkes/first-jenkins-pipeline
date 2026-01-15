/* Jenkinsfile (Declarative Pipeline) */
/* Requires the Docker Pipeline plugin */
pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                ansiColor('xterm') {
                    sh 'echo -e "\\033[31mI\'m Red\\033[0m Now not"'
                    sh 'echo -e "\\033[31mHello World"'
                    sh '''
                        echo "Multiline shell\\033[0m steps works too!"
                        ls -lah
                    ''' 
                }
                
            }
        }
    }
}
