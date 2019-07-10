node {
    
    stage('scm') {
    // some block
    git 'https://github.com/wakaleo/game-of-life.git'
    }
    stage('build') {
    // some block
     bat label: '', script: 'mvn package sonar:sonar'
    }
    
}
