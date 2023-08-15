pipeline {
    agent {
      node { label 'workstation' }
    }

    stages {

      stage ('Build') {
        steps {
          echo 'Build'
        }
      }

      stage ('Unit-Tests') {
        steps {
          echo 'Unit-Tests'
        }
      }

      stage ('Code-Analysis') {
        steps {
          echo 'Code-Analysis'
        }
      }

      stage ('Security Checks') {
        steps {
          echo 'Security Checks'
        }
      }

      stage ('Publish Artifact') {
        steps {
          echo 'Publish Artifact'
        }
      }
    }
}