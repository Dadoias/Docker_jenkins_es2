pipeline{
    agent{
        docker{
            image 'davideias/ubuntu_environment:latest'
        }
    }
    stages{
        stage('boh') {
            steps {
                sh 'pwd'
                sh 'ls'
                //sh 'cd ~/Desktop'
                sh 'touch test.txt'
                sh 'ls'
            }
        }
    }
}
   
