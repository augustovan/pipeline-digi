pipeline {
   agent any

   stages {
      stage('Build') {
         steps {
            echo 'Iniciando os Trabalhos'
            }
        }
      stage('Test') {
         steps {
            echo 'Testado com Sucesso'
            }
        }
      stage('Homologation') {
         steps {
            echo 'Teste de Homogação na URL: http://ec2-34-238-121-46.compute-1.amazonaws.com:82/'

            }
        }
      stage('Production') {
         steps {
            echo 'Colocado em Produção '
            echo 'Acesso ao ambiente de Produção via URL: http://ec2-34-238-121-46.compute-1.amazonaws.com'
            }
        }
    }
}