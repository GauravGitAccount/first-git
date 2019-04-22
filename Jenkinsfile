pipeline{
  agent any
    stages{
      stage('build'){
        steps{
          echo 'hello world'
        }
      }
      stage('test'){
        steps{
          input('proceed')
        }
      }
  }
}
