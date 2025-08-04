pipeline {
    agent any
    stages {
        stage('Info') {
            steps {
                echo "Repo: ${env.GIT_URL}"
                echo "Branch: ${env.BRANCH_NAME}"
            }
        }
    }
}
