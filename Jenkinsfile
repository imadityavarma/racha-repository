pipeline{
    agent any
    stages{
        stage("maven"){
            when {
                branch "develop"
            }
            steps{
                sh "mvn package"
            }
        }
        stage("deploy to prod"){
            when {
                branch "master"
            }
            steps{
                echo "hello aditya"
            }
        }
    }
}
