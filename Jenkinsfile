node {
    checkout scm
    docker.withRegistry('https://registry.hub.docker.com/u/mayuriisable', 'dockerHub') {
        def customImage = docker.build("mayurii/dockerwebapp")
        /* Push the container to the custom Registry */
        customImage.push()
   }

}
