pipeline {
    agent any 
    stages {
        stage ('test') {
            steps {
                echo "runinng01"
            }
        }
        stage ('Build') {
            environment {
                NAME = "shadal"
            }
            steps {
                sh = sleep(20)
                echo "My name is ${NAME}"
                
            }
        }
    }
}
