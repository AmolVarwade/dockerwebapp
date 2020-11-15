node {

    checkout scm



    docker.withRegistry('https://https://registry.hub.docker.com', 'dockerhub') {



        def customImage = docker.build("mywebapp}")



        /* Push the container to the custom Registry */

        customImage.push()

    }

}
