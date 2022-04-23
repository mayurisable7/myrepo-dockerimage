node {
    checkout scm
    docker('https://hub.docker.com/', 'dockerHub') {
        def customImage = docker.build("mayuri/dockerwebapp")
        /* Push the container to the custom Registry */
        customImage.push()
   }

}
