node {

   stage('Clone Sockshop from github') {

       git 'https://github.com/PA-Playground/microservices-demo.git'

   }

   stage('Build and deploy Sockshop') {
      //withDockerRegistry(credentialsId: 'ecr:eu-west-1:aws_access_id', url: 'https://826081382146.dkr.ecr.eu-west-1.amazonaws.com') {
       sh "docker-compose -f deploy/docker-compose/docker-compose.yml up -d"
      //}
   }

}
