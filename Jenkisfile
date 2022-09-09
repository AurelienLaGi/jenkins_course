pipeline{
    agent any
    stages{
        stage("Etape 1") {
            steps {
                echo 'Debut etape 1'
                echo 'Fin step 1'
            }
            post {
                always {
                    echo 'Fin etape 1 - passage etape 2'
                }
            }
        }
        stage("Etape 2") {
            steps {
                echo 'Debut etape 2'
                echo 'Fin step 2'
            }
        }
    }
}