pipeline {
    agent any

    stages {
        stage('Gt-checkout') {
            steps {

                echo "checking out from github"
                // Get some code from a GitHub repository
                git 'https://github.com/arturgeller6/pipeleine_script.git'


            }
        
        }
        
        stage('Build') {
            steps {

                echo "building chcked out project"
                sh 'ls -l'
                sh 'chmod +x Build.sh'
                sh 'ls -l'
                sh './Build.sh'
            }
        
        }
        
        
    }
}
