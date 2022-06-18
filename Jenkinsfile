pipeline {
    agent any
    stages {
        stage ("Build") {
            steps {
                sh 'echo "Welcome to Fully Cloud Solutions"'
                sh '''
                     echo "Testing shell scripts to see what works"
                    ls -lah
                    '''
            }
        }
        stage('Lint HTML') {
            steps {
                sh 'tidy -q -e *.html'
              }
         }
    }
}
