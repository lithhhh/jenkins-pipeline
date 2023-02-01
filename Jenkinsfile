node() {
    stage('teste') {
        checkout scm
    }

    witchCredentials([string(credentialsId: 'teste', variable: 'TESTE')]) {
        echo(message: '$TESTE')
    }
}