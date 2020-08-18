pipeline {
    agent any
    stages {
        stage('CheckOut Stage') {
            steps {
                echo "Updates files in  the working tree to match the version in the index or sprecified tree."
                checkout scm
            }
        }
        stage('build') {
            steps {
                echo "My trial jenkins code"
            }
        }
    }
}