node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerhub') {

        def customImage = docker.build("jyothi47/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}