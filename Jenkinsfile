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
                sh = sleep(30)
                echo "My name is ${NAME}"
                
            }
        }
    }
}
