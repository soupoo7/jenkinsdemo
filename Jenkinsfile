pipeline {
    agent any

    stages {
        stage('Git Checkout') {
            steps {
                git 'https://github.com/soupoo7/java-tomcat-maven-docker.git'
            }
        }
        stage ('Execute'){
            steps{
                // exit 1
                echo "Hello Soup"
            }
            
        }
        stage ('EXIT'){
            steps {
                sh ''' ls -lart '''
            }
        }
    }
}
