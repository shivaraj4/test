pipeline {

  agent {
    any
  }

  parameters { 
    choice(name: 'PERFORMANCE_TEST_IN_DEV', choices: ['no', 'yes'], description: 'Do you wish to perform performance testing in DEV environment on this build?')
    choice(name: 'REGRESSION_TEST_IN_DEV', choices: ['yes', 'no'], description: 'Do you wish to perform regression testing in DEV environment on this build?')
  }
  
stages {

    stage('hello'){
      steps {
        sh '''
          echo "hello"
        '''
      }        
    }
   }
  } 
