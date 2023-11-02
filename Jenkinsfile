pipeline {
    agent any

    stages {
        stage('Print') {
            steps {
                bat '''
                    dir
                    cd
                    date /t
                    time /t
                '''
            }
        }
    }
}
