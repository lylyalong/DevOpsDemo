pipeline {
  any agent

  stages {

    stage ('Checkout') {
      steps {
        echo 'Start checkout source from remote site'
        git url:'https://github.com/lylyalong/DevOpsDemo.git', branch:'main',credentialsId:'c165da9a-00c9-47a7-9a8e-0d25ad3a3a50'    
        echo 'Finish checkout source from remote site'
      }
    }

    stage ('Build') {
      steps {
        echo 'Start build the package'
        echo 'Finish build the package'
      }
    }

    stage ('Deploy') {
      steps {
        echo 'Start deploy the package'
        echo 'Finish deploy the package'
      }
    }
    
  }
  
}
