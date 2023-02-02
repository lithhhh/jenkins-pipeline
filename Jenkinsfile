node {
    stage('teste 2') {
        withCredentials([string(credentialsId: 'teste', variable: 'TESTE')]) {
            sh "echo meu teste $TESTE"
        }
    }
}
