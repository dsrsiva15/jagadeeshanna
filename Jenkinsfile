pipeline {
    agent any
stages {
        stage('Example Build') {
            steps {
                sh 'touch $BUILD_NUMBER' 
                sh 'ls -ltr'
}
}
        stage('cleanup'){
            steps{
               sh 'rm -rf $WORKSPACE/*'
            }
            }
        }
}
