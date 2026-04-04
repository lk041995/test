pipeline {
    agent any
    
    stages{
        stage("hostname"){
            stage{
                sh "hostname"
            }
        }
        stage("date"){
            stage{
                sh "date"
            }
        }
        stage("uptime"){
            stage{
                    sh "uptime"
            }
        }
        stage("free"){
            stage{
                    sh "free -h"
            }
        }     
    }
}
