pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git url: 'https://github.com/DivyaJPofficial/python-for-devops.git', branch: 'main'
            }
        }
        
 
        stage('Run Python Script') {
            steps {
                // Run the specific Python script
                sh 'python3 Day-01/02-hello-world.py'
            }
        }
    }
}
