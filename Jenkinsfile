#!/groovy

pipeline
{
    agent any
    stages{
        stage('Cleaning Working Directory')
        {
            steps{
                echo 'started the cleaning'
                deleteDir()
            }
        }
        stage('cloning')
        {
            steps{
                checkout scm
            }
        }
    }
}
