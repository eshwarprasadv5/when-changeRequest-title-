pipeline{
    agent any
    stages{
        stage('Build'){
            when{
                changeRequest title:"PR-1"
            }
            steps{
               echo "PR-1 build done"
            }
        }
    }
}
