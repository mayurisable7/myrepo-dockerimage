node {
    checkout scm
    docker.withRegistry('https://hub.docker.com/u/mayuriisable', 'dockerHub') {
        def customImage = docker.build("mayuri/dockerwebapp")
        /* Push the container to the custom Registry */
        customImage.push()
   }

}
