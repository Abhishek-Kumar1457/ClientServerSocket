pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building'
                sh "sh script.sh"
            }
        }
        stage('Push Release') {
        steps {
          script {
            echo "Released"
            sh "g++ main.cpp"
            sh "./a.out"
        }
    }
}
    stages {
        stage('Deploy') {
            steps {
                echo 'Deploy'
            }
        }
    }
}
