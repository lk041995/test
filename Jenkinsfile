pipeline {
    agent any

    stages{
        stage("hostname"){
            steps{
                sh "hostname"
            }
        }
        stage("date"){
            steps{
                sh "date"
            }
        }
        stage("uptime"){
            steps{
                sh "uptime"
            }
        }
        stage("free"){
            steps{
                sh "free -h"
            }
        }     
    }
}
