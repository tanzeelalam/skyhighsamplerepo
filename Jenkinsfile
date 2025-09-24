@Library("my-library") _

pipeline {
    agent any

    stages {
        stage('checkout') {
            steps{
                checkoutRepo()
            }
        }
        stage('Hello') {
            steps {
                echo 'Mohammed Tanzeel Alam'
            }
        }
    }
}

