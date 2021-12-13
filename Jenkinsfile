#!groovy
pipeline {
    agent {label 'DEV-TST4-RH'}

    stages {
        stage('First') {
            steps {
                
                sh '/root/insertsql.pl pqa3 13 192.10.9.8 1 inserting'
            }
        }
        stage('Second') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Three') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
