pipeline{
    agent any
    environment{

    }
    stages{
        stage("clone the repo"){
            steps{
                git url :"", branch: ""
            }
        }
    }
    stages{
        stage("run docker compose"){
            steps{
                script{
                    bat "docker-compose up"
                }
            }
        }
    }
}