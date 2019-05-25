node
{
    stage('SCM Checkout')
    {
      git 'https://github.com/Shan12196/demo'
    }
    stage ("maven") {
        withMaven(maven: 'Maven 3.5.4', java: 'jdk7'){
            sh './mvn clean install'
        }
    } 
}

