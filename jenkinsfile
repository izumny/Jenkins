node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("iankure/dockerpractice")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
