pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Building'
        emailext(subject: 'Build Complete', body: 'The build is complete', from: 'paul@paulrigney.net', replyTo: 'paul.rigney@gmail.com', saveOutput: true, to: 'paul.rigney@gmail.com')
      }
    }

    stage('Test') {
      steps {
        echo 'Testing'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}