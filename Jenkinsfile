node
{
    stage('SCM Checkout')
    {
      git 'https://github.com/mybatis/jpetstore-6.git'
    }
    stage ("maven") {
        withMaven(maven: 'maven', java: 'jdk8'){
            sh 'mvn clean install'
        }
    } 
}

