node {
    stage('Clone sources') {
        git url: 'https://github.com/atingupta2005/docker-compose-example-python.git'
    }
    stage('Docker Compose Delete') {
      sh "docker-compose down"
    }

    stage('Docker Compose Up') {
      sh "docker-compose up -d"
    }

  
}
