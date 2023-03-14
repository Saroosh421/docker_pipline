pipeline {
  agent any
  
  stages {
    stage('Build') {
      steps {
        sh 'docker build -t temp:latest .'
      }
    }
    // stage('Test') {
    //   steps {
    //     sh 'docker run temp python app.py'
    //   }
    // }
    // stage('Deploy') {
    //   steps {
    //     sh 'docker run -d -p 8500:8500 temp'
    //   }
    // }
    // stage('Expose') {
    //   steps {
    //     ngrok([httpPort: 5000])
    // }
    //}
}
}