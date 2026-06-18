pipeline{
    agent any
    stages{
        stage("Restore packages"){
            steps{
                bat 'dotnet restore'
            }
        }
        stage("Build the project"){
            steps{
                bat 'dotnet build'
            }
        }
        stage("Run tests"){
            steps{
                bat 'dotnet test'
            }
        }
    }
}