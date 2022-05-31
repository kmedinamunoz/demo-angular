pipeline {
    agent {label 'windows'}
    
//     options { skipDefaultCheckout() }

    stages {
        stage('Install Dependencies') {
            steps {
                sh 'npm install'
            }
        }
        stage('Unit Test') {
            steps {
                echo 'Ejecutar Unit Test'
            }
        }
        stage('Build') {
            steps {
                sh 'ng build'
            }
        }
    }
}
