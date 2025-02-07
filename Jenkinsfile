pipeline {
    agent any
    stages {
        stage("Build") {
            steps {
                echo ("Start Build")
                sh("./mvnw clean compile test-compile")
                echo ("Finish Build")
            }
        }
        stage("Test") {
            steps {
                echo ("Start Test")
                sh("./mvnw test")
                echo ("Finish Test")
            }
        }
        stage("Deploy") {
            steps {
                echo ("Start Deploy")
                echo ("Finish Deploy")
            }
        }
    }
}