pipeline {
    agent any
    
    stages {

        stage('build') {
            steps {
                sh 'touch demo.py'
            }
        }
        stage('Test') {
            steps {
                sh 'python3 test.py'
    }
}
       
    }
}
