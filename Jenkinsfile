pipeline {

    agent any

    tools {nodejs "nodejs1"}

    stages {

        stage('Hello') {

            steps {

                echo 'Hello World'

            }

        }

        stage('Dev') {

            steps {

                git 'https://github.com/awstrainersz/test-demogit'

                echo 'content of my file is'

                sh 'cat file1.txt'

            }

        }

        stage('node build') {

            steps {

                sh 'npm install'

            }

        }

    }

}
