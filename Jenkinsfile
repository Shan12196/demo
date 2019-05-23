node
{
    tool{
        maven 'Maven 3.5.4' 
        java 'jdk7' 
    }
    stage('SCM Checkout')
    {
      git 'https://github.com/Shan12196/demo'
    }
    stage ("initialize") {
        steps {
        sh '''
        echo "PATH = ${PATH}"
        echo "M2_HOME = ${M2_HOME}"
        '''
        }
    } 
}

