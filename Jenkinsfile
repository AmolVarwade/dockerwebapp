node {

    checkout scm



    docker.withRegistry('https://https://registry.hub.docker.com', 'dockerhub') {



        def customImage = docker.build("amol/simplewebapp}")



        /* Push the container to the custom Registry */

        customImage.push()

    }

}
