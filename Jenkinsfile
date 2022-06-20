  // Declarative pipeline
pipeline {
    agent any

    stages {

        stage ('Git Checkout') {
            steps {
                    git branch: 'main', credentialsId: 'github', url: 'https://github.com/raghavendra1991/docker_pipeline.git'
                }
          }
        
     }
}
