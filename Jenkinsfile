node {
    
    stage('scm') {
    // some block
    git 'https://github.com/wakaleo/game-of-life.git'
    }
    stage('build') {
    // some block
     bat label: '', script: 'mvn package'
    }
    stage('artifacts') {
    archiveArtifacts 'archiveArtifacts 'gameoflife-web/target/*.war''
    }
}
