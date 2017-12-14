pipeline {
  agent any
  stages {
    stage('Commit Stage / Build') {
      parallel {
        stage('Commit Stage / Build') {
          steps {
            echo 'Commit Stage'
          }
        }
        stage('Pull dependencies') {
          steps {
            echo 'Pull dependencies'
          }
        }
        stage('Build') {
          steps {
            echo 'Build'
          }
        }
        stage('Unit Test') {
          steps {
            echo 'Unit Test'
          }
        }
      }
    }
    stage('Dev Test Stage / Code Quality') {
      parallel {
        stage('Development Test Stage / Code Quality') {
          steps {
            echo 'Dev test stage'
          }
        }
        stage('Static code analysis') {
          steps {
            echo 'Static code analysis'
          }
        }
        stage('Dynamic code analysis') {
          steps {
            echo 'Dynamic code analysis'
          }
        }
        stage('Security analysis') {
          steps {
            echo 'Security Analysis'
          }
        }
        stage('Profiler / Code Review tools') {
          steps {
            echo 'prof code review'
          }
        }
        stage('Component test') {
          steps {
            echo 'component test'
          }
        }
        stage('Integration test') {
          steps {
            echo 'int test'
          }
        }
        stage('Acceptance test') {
          steps {
            echo 'acceptance test'
          }
        }
      }
    }
  }
}