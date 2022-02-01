

pipeline {
  agent any
    parameters([
        string(name: 'testPlanKey', defaultValue: ''),
        string(name: 'targetIteration', defaultValue: 'NEW_ITERATION'),
        string(name: 'testCaseCreationStrategy', defaultValue: 'CREATE_AND_UPDATE')
        string(name: 'testFloImportResultsParameters', defaultValue: '')     
    ])
  stages {
    stage('hello') {
      steps {
        echo 'hello'
      }
    }

  }
}
