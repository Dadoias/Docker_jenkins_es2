pipeline{
    agent{
        docker{
            image 'davideias/ubuntu_environment:latest'
        }
    }
    stages{
        stage('boh') {
            steps {
                sh 'cd ..'
                sh 'pwd'
                //sh 'cd ~/Desktop'
                //sh 'touch test.txt'
            }
        }
    }
}
   
