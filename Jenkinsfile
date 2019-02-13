node
{
    stage('Checkout')
    {
       checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/Sohail8095/time-tracker']]])
       workspace =pwd()
    }
    stage('Stage code analysis')
    {
        echo "static code analysis"
    }
    stage('Build')
    {
        echo "Build the code"
    }
    stage('Unit testing')
    {
        echo "Unit testing"
    }
    stage('Delivery')
    {
        echo "Deliver the code"
    }
}
