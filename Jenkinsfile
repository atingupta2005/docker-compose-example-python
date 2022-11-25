node {
    stage('Docker Compose Up') {
      sh "rm -rf docker-compose-example-python"
      sh "git clone https://github.com/atingupta2005/docker-compose-example-python.git"
      sh "cd docker-compose-example-python; pwd; ls -alh"
      sh "docker-compose up -d"
    }

  
}
