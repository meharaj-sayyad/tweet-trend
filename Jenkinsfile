pipeline {
    agent  {
          node {
                 label 'maven'
          }
    }

    stages {
        stage('Cloned-code') {
            steps {
                git branch: 'main', url: 'https://github.com/ravdy/tweet-trend-new.git'
            }
        }
    }
}
