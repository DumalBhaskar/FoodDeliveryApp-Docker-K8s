pipeline {
    agent any
   
    stages {
        
        stage('deploy to staging') {
            when {
                branch 'develop'
            }
            steps {
               script {

                    echo "Deploying to staging environment..."
               }
            }

        }
        stage('Deploy to production') {
            when {
                branch 'main'  
            }
            steps {
                script {

                    echo "Deploying to production environment..."
                }
            }
        }
    }
}
