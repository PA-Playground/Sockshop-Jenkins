node {

   stage('Clone Sockshop from github') {

       git 'https://github.com/PA-Playground/microservices-demo.git'

   }

   stage('Build and deploy Sockshop') {

       sh "docker-compose -f deploy/docker-compose/docker-compose.yml up -d"

   }

}
