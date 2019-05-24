node
{
    stage('SCM Checkout')
    {
      git 'https://github.com/Shan12196/demo'
    }
    stage ("maven") {
        withMaven(jdk: 'jdk7', maven: 'Maven 3.5.4'){
            sh 'mvn clean install'
        }
    } 
}

