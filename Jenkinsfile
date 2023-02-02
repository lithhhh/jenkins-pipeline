node {
    stage('teste 2') {
        withCredentials([string(credentialsId: 'teste', variable: 'TESTE')]) {
            echo(message: $TESTE)
        }
    }
}
