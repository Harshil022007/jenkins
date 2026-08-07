pipeline {
    agent any
    satges {
        stage('hello'){
          stage('world'){
            steps{
                echo "Hello world"
              }
            }
        }
    }
}
post{
    success{
        echo "Pipeline failed4r.Please check the logsb for details"
    }
}
