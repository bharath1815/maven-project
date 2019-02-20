import hudson.plugins.git.*

    node {

        stage('HelloWorld') {
            echo "Hello World"
        }
        stage('compile') {
      steps {
        sh 'mvn clean install'
      }
    }
    }
