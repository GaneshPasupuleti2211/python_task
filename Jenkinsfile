pipeline {
agent any
stages {
        stage('Build') {
                steps {
                    echo 'Building.. app'
                    }
                }
        stage('Test') {
                steps {
                    echo 'Testing.. app'
                    }
                }
        stage('Deploy') {
                steps {
                    echo 'Deploying.... app'
                    }
                }
           }
            
        post{
                always{
              emailext body: 'Build Success fully Done...!!!', subject: 'Pipeline Status', to: 'ganeshpasupuleti2211@gmail.com'
                }
   }}
    
