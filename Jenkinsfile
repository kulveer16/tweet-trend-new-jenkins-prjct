pipeline{
    agent {
        node{
            label 'maven'
        }
    }
    stages{
        stage('clone'){
            steps{
               git branch: 'main', url: 'https://github.com/kulveer16/tweet-trend-new-jenkins-prjct.git'
            }
        }
    }
}