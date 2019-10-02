def workspace
node{
    stage('Checkout'){
        checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: '9ffd0352-1416-4b96-8e5f-783521a1ea60', url: 'https://github.com/jayanthrajanna/testrepository.git']]])
        workspace = pwd()
        
    }
    stage('Static COde Analysis'){
        echo "Static COde Analisuss"
    }
    stage('build'){
        echo "build the code"
    }
    stage('Unit Testing'){
        echo "unit testing"
    }
    stage('Delivery'){
        echo "delivery"
    }
}
