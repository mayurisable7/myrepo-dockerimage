node {
    checkout scm
    docker.withRegistry('https://mayurisable0720sl0034.simplilearnlabs.com:42001/guacamole/#/client/REVGQVVMVABjAGRlZmF1bHQ=?username=guacadmin&password=guacadmin', 'dockerHub') {
        def customImage = docker.build("mayuri/dockerwebapp")
        /* Push the container to the custom Registry */
        customImage.push()
   }

}
