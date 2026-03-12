pipeline {
  agent any
  stages{
    
  stage('Clone'){
    steps{
      git url: 'https://github.com/msaishwarya37-netizen/jenkins-simple-demo.git',
        branch: 'main'
    }
  }
  stage('Run Script'){
    steps{
      sh 'chmod +x script.sh'
      sh './script.sh'
    }
  }
}
}
