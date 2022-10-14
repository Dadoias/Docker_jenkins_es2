pipeline{
    agent{
        docker{
            image 'davideias/myrepository:latest'
        }
    }
    stages{
        stage('boh') {
            steps {
                sh 'echo "Davide"'
                //sh 'docker run davideias/myrepository '  
            }
        }
    }
}
