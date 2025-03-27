pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac Hello.java' // Compiling Hello.java
            }
        }
        
        stage('Run') {
            steps {
                bat 'java Hello' // Running Hello.java
            }
        }
    }
}
