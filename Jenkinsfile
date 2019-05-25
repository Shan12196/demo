node
{
    stage('SCM Checkout')
    {
      git 'https://github.com/Shan12196/demo'
    }
    stage ("maven") {
        withMaven(){
            sh './mvn clean install'
        }
    } 
}

