node {
      checkout scm
      
      docker.withRegistry('https://registry.hub.docker.com','docker-hub'){
        def customImage = docker.build("sharmh34/dockerwebapp")
        
        customImage.push()
        }
}        
