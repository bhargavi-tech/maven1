pipeline {

        agent 'any'

        stages {
                stage ('checkout') {
                steps {
                        echo 'checkout'
                        git url: 'https://github.com/Devisetty99/example-java-maven'
                                }
                        }
                stage ('build') {
                        steps {
                                echo 'clean build'
                                sh 'mvn compile'
                                }
                        }
                stage ('test') {
                        steps {
                                echo 'testing'
                                sh 'mvn test'
                                }
                        }
                }
         }

