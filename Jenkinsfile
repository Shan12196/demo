node
{
    stage('SCM Checkout')
    {
      git 'https://github.com/Shan12196/demo'
    }
    stage ("maven") {
        withMaven(maven: 'maven', java: 'jdk7'){
            sh './mvn clean install'
        }
    } 
}

