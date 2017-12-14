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
    stage('Development Test Stage / Code Quality') {
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
      }
    }
  }
}