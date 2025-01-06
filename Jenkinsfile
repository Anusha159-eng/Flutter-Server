pipeline{
    agent any
    tools {nodejs "Node"}
    stages {
        stage('Build'){
            steps{
                git branch: 'main',
                    url: 'https://github.com/MIRTAHAALI/express_server_for_flutter_app_testing.git'
            }
        }
      stage('Test') {
            steps {
                echo 'Testing...'
            }
         }
        stage('Deploy'){
            steps {
                echo 'Deploying...'                
            }
        }
    }
}
