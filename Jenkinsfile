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
        stage("rune docker compose"){
            steps{
                script{
                    bat "docker-compose up -d --build"
                }
            }
        }
    }
}