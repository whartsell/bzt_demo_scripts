node {
   stage('build') {
      git 'https://github.com/whartsell/bzt_demo_scripts.git'
   }
   
   stage('test') {
     sh 'bzt ./scripts/test_hello.yml'
  }
}

