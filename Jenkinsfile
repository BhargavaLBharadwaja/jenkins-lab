pipeline{
  agent any
  stages{
    stage('Clone'){
      steps{
        git url: "https://github.com/BhargavaLBharadwaja/jenkins-lab.git",branch:"main"
      }
    }
    stage('Run Script'){
      steps{
        sh 'chmode +x script.sh'
        sh './script.sh'
    }
  }
  }
}
