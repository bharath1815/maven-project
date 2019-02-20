import hudson.plugins.git.*

    node {

        stage('HelloWorld') {
            echo "Hello World"
        }
        stage('Clean Maven') {
            steps {
                sh "clean package"
            }

        }
    }
